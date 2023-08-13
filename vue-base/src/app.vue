<template>
    <p>{{ msg }}</p>
    <p>{{ hello }}</p>
    <p>{{ number+1 }}</p>
    <p>{{ ok?'Yes':'No' }}</p>
    <p v-html="rawHtml"></p>
</template>
<script>
export default{
    data(){
        return{
            msg:"神奇的语法",
            hello:"Hello,World",
            number:10,
            ok:true,
            rawHtml:"<a href='https://baidu.com'>baidu</a>"
            
        }
    }
}
</script>
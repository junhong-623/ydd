<template>
    <header id="header">
        <slot></slot> <h1>{{ title }}</h1>
    </header>
</template>

<script>
export default {
    name : 'Header',
    props : {
        title : {
            type : String,
            default : '多多电影'
        }
    }
}
</script>

<style scoped>
#header{width:100%; height:50px; color: #fff; background: #7219d6; border-bottom: 1px solid #7219d6; position: relative;}
#header h1{ font-size: 18px; text-align: center; line-height: 50px; font-weight: normal; }
#header i{ position: absolute; left: 5px; top: 50%; margin-top: -13px; font-size: 26px;}
</style>

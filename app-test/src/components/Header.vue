<script setup lang="ts">
import { ref } from 'vue'
const name= ref<string>('yuki')
</script>

<template>
    <div id="headWrap">
        <h1>ToDo List</h1>
        <p>ようこそ{{ name }}さん</p>
    </div>
</template>

<style scoped>
    h1, p{
        color: rgb(255, 255, 255);
    }
    #headWrap {
        display: flex;
        justify-content: space-between;
        height: 50px;
        background-color: rgb(31, 155, 58);
    }
    #headWrap h1 {
        margin-left: 20px;
    }
    #headWrap p {
        height: 100%;
        line-height: 50px;
        margin-right: 20px;
    }
</style>
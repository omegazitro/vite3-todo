<template>
  <header class="flex flex-col w-full container">
    <Title msg="🎲 My Bucket List 🎲" />
    <NewTodo />
  </header>
</template>

<script setup>
import Title from './Title.vue'
import NewTodo from './NewTodo.vue'
</script>
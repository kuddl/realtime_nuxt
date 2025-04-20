<script setup lang="ts">
const message = 'Hello World';
const message2 = 'Hello World';

console.log(`💡 ~ app.vue:3 ~ message:`, message);
console.log(`💡 ~ app.vue:3 ~ message:`, message2);
</script>

<template>
  <div>
    <h1>Hello World</h1>
    <p>{{ message }}</p>
    <p>{{ message2 }}</p>
  </div>
</template>

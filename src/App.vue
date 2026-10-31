<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <main>
    <h1>Hello from Vue!</h1>
    <button type="button" @click="count++">Clicked {{ count }} times</button>
    <p>Edit <code>src/App.vue</code> and deploy again.</p>
  </main>
</template>

<style>
body {
  font-family: system-ui, sans-serif;
  margin: 4rem auto;
  max-width: 40rem;
  padding: 0 1rem;
}
</style>

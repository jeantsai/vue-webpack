<script setup>
  import { ref } from 'vue';

  const count = ref(0);
  const msg = ref('world')
</script>

<template>
  <div>
    <p>{{ count }}</p>
    <button @click="count += 1">点击加一</button>
    <hr />
    <p>Hello {{ msg }}</p>
    <input v-model="msg"></input>
  </div>
</template>
<template>
  <div>
    {{ saludo }}
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const saludo = ref('Hola a todos')
</script>

<style scoped></style>

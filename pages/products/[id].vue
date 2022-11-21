<template>
  <div>product details for {{ id }}</div>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur cum
    distinctio suscipit minima, eos corporis corrupti sequi quos iste qui
    architecto nam, incidunt enim sint nostrum maxime porro amet at.
  </p>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style scoped>
</style>
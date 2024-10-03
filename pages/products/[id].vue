<template>
  <div>
    <p>Product details for {{ id }}</p>

    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Neque, soluta
      aspernatur quo, ab facilis excepturi eum eaque quas, suscipit totam ut et
      molestiae consectetur corporis quis saepe quasi. Distinctio, possimus.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params

definePageMeta({
  layout: 'products',
})
</script>

<style scoped></style>

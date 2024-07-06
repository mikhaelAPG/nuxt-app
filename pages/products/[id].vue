<template>
  <div>
    <p>Products detail for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, ducimus
      quaerat laudantium officia aliquam quidem eligendi impedit! Laudantium,
      voluptate maxime.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta({
  layout: "products",
});
</script>

<style scoped></style>

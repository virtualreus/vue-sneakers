<script setup>
import CartItem from './CartItem.vue'
</script>

<template>
  <div class="flex flex-col gap-4 flex-1 card-list">
    <CartItem />
    <CartItem />
    <CartItem />
    <CartItem />
    <CartItem />
  </div>
</template>

<style scoped>
.card-list {
  max-height: 70%;
  overflow: scroll;
}
</style>

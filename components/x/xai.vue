<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydwd7ibnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xai" /></template>
<style>
.ydwd7ibnq {
  fill: var(--svg-color--ff253a, #ff253a);
  fill-rule: evenodd;
  d: path("M15.669 16.716H8.332l2.614-4.53L9.17 9.11L3 19.794h18L12 4.206l-1.777 3.078z");
}

</style>

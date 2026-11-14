<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulmovpbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shapewear" /></template>
<style>
.ulmovpbma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h10c0 3-1 4.5-1 6.5s3 3.5 3 6v5h-5.5v-3q-1.5-1.5-3 0v3H5v-5c0-2.5 3-4 3-6S7 5.5 7 2.5ZM8 9h8M5 18h5.5m3 0H19");
}

</style>

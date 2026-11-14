<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w16z15b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartphone-nfc" /></template>
<style>
.w16z15b_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h10.5v19H4ZM8 18h2.5m7.181-8.25a3.5 3.5 0 0 1 0 4.5m2.298-6.428a6.5 6.5 0 0 1 0 8.356");
}

</style>

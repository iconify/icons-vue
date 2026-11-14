<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxpwxmbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:receipt-printer" /></template>
<style>
.rxpwxmbsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11.5h11A3.5 3.5 0 0 1 21 15v2a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-2a3.5 3.5 0 0 1 3.5-3.5m1 0V5L9 3.5L10.5 5L12 3.5L13.5 5L15 3.5L16.5 5v6.5M10 8.25h4M17 16h.01");
}

</style>

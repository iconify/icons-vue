<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4a6v64od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wash-bottle" /></template>
<style>
.n4a6v64od {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.375 10h3.25A4.375 4.375 0 0 1 16 14.375v2.75a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 4 17.125v-2.75A4.375 4.375 0 0 1 8.375 10M9 7h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 11 10H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 7m1 0V3.5h5.5l2 2.5m1.25 2.75L20 11.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix9x-m3es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smooth-legs" /></template>
<style>
.ix9x-m3es {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 2.5h6.75A2.625 2.625 0 0 1 16 5.125v.75A2.625 2.625 0 0 1 13.375 8.5h-6.75A2.625 2.625 0 0 1 4 5.875v-.75A2.625 2.625 0 0 1 6.625 2.5M10 8.5l-2 13m-1.5-16h7m4.5 8q0 4 4 4q-4 0-4 4q0-4-4-4q4 0 4-4");
}

</style>

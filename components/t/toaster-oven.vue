<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtuecs9vi"/><path class="hg6hizbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toaster-oven" /></template>
<style>
.hg6hizbsq {
  d: path("M7.25 7.75h6A1.75 1.75 0 0 1 15 9.5v2a1.75 1.75 0 0 1-1.75 1.75h-6A1.75 1.75 0 0 1 5.5 11.5v-2a1.75 1.75 0 0 1 1.75-1.75M5.5 16H15m3.5-6.5h.01M18.5 13h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtuecs9vi {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5");
}

</style>

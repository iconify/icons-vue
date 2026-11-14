<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jaze0sbcr"/><path class="b1o1yjb8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-sale-poster" /></template>
<style>
.b1o1yjb8q {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M9 19l6-5.5M8 14a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 8 14m5.5 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jaze0sbcr {
  d: path("m3 9l1.5-5h15L21 9M5.75 11h12.5A1.75 1.75 0 0 1 20 12.75v7a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 19.75v-7A1.75 1.75 0 0 1 5.75 11");
}

</style>

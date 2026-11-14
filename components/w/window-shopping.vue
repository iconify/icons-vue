<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jaze0sbcr"/><path class="awke0yb6j"/><path class="qsq2gsqla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-shopping" /></template>
<style>
.awke0yb6j {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 16.25c2-2.75 9-2.75 11 0c-2 2.75-9 2.75-11 0");
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

.qsq2gsqla {
  d: path("M10.5 16.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>

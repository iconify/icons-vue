<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qjar_zbba"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presence-simulation" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qjar_zbba {
  d: path("M8.213 2.5h3.574a1.75 1.75 0 0 1 1.639 1.136l1.687 4.5a1.75 1.75 0 0 1-1.638 2.364h-6.95a1.75 1.75 0 0 1-1.638-2.364l1.687-4.5A1.75 1.75 0 0 1 8.213 2.5m1.787 8v10m-3.5 0h6m2.25-2.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>

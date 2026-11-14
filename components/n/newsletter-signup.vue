<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xef_tc00d"/><path class="xye4ag6lj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:newsletter-signup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xef_tc00d {
  d: path("M8.625 2.5h6.75A2.625 2.625 0 0 1 18 5.125v3.25A2.625 2.625 0 0 1 15.375 11h-6.75A2.625 2.625 0 0 1 6 8.375v-3.25A2.625 2.625 0 0 1 8.625 2.5M6 14h12a3.5 3.5 0 0 1 3.5 3.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 14");
}

.xye4ag6lj {
  d: path("M8.5 5.5L12 8l3.5-2.5M6 17.5h8");
}

</style>

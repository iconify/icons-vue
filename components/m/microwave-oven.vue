<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6_jkr2cj"/><path class="bt6idx30d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microwave-oven" /></template>
<style>
.bt6idx30d {
  d: path("M7.75 8h5a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 12.75 16h-5A1.75 1.75 0 0 1 6 14.25v-4.5A1.75 1.75 0 0 1 7.75 8M17 9h.01M17 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6_jkr2cj {
  d: path("M7.375 5h9.25A4.375 4.375 0 0 1 21 9.375v5.25A4.375 4.375 0 0 1 16.625 19h-9.25A4.375 4.375 0 0 1 3 14.625v-5.25A4.375 4.375 0 0 1 7.375 5");
}

</style>

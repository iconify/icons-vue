<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hr5r2wb3n"/><path class="a5qbfx8kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:planet-star" /></template>
<style>
.a5qbfx8kc {
  d: path("M6 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0M18.5 2q.75 2.75 3.5 3.5q-2.75.75-3.5 3.5q-.75-2.75-3.5-3.5q2.75-.75 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr5r2wb3n {
  d: path("M2 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpij-bljr"/><path class="bjwmrvu0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rowan-berries" /></template>
<style>
.bjwmrvu0p {
  fill: currentColor;
  d: path("M2.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M9 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.5-2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zpij-bljr {
  d: path("M11 9c1-4 4.5-6 10-6c-.5 4.5-5 6.5-10 6m0 0l-6.5 5.5M11 9v8m0-8l8.5 5.5");
}

</style>

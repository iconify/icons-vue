<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="inbeesb1t"/><path class="bj0d-s1lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-cable-lock" /></template>
<style>
.bj0d-s1lc {
  d: path("M5.5 8.5a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0M15.625 15h3.25a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 13 18.875v-1.25A2.625 2.625 0 0 1 15.625 15M15 15v-1.5a2.25 2.25 0 0 1 4.5 0V15M6 13.5c0 3.5 2.5 4.75 7 4.75m4.25 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.inbeesb1t {
  d: path("M2.5 8.5a6 5.5 0 1 0 12 0a6 5.5 0 1 0-12 0");
}

</style>

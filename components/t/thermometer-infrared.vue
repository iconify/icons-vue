<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="deqcjr2bt"/><path class="ts82sdbrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thermometer-infrared" /></template>
<style>
.deqcjr2bt {
  d: path("M9 4h10.5c1.1 0 2 .9 2 2v2.5c0 1.1-.9 2-2 2H19l.5 9c.1 1.1-.75 2-1.75 2H16c-1 0-1.75-.75-1.75-1.75L14 10.5H9c-.9 0-1.5-.6-1.5-1.5V5.5C7.5 4.6 8.1 4 9 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ts82sdbrb {
  d: path("M11.5 10.5c0 1.5.75 2.5 2.25 2.5M2.5 4.5L5.25 6M2.5 10l2.75-1.5");
}

</style>

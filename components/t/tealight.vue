<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rouiohywq"/><path class="bpg3p4imn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tealight" /></template>
<style>
.bpg3p4imn {
  d: path("M5 13v3.75c0 1.75 3 3 7 3s7-1.25 7-3V13m-7-5c-1.4-.85-1.5-2.5 0-4.5c1.5 2 1.4 3.65 0 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rouiohywq {
  d: path("M5 13a7 2.25 0 1 0 14 0a7 2.25 0 1 0-14 0");
}

</style>

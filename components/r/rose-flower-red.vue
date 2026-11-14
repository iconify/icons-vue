<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wy405q1uw"/><path class="qiqw9wbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rose-flower-red" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qiqw9wbad {
  d: path("M14 9.25a2 2 0 1 1-2-2m0 11.25c0-2.5 2-3.5 5-3.5c0 2.5-2 3.5-5 3.5");
}

.wy405q1uw {
  d: path("M6 8c0-3.5 3-5.5 6-3.5c3-2 6 0 6 3.5A6 6 0 0 1 6 8m6 6v7.5");
}

</style>

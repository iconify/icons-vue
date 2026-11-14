<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cl777l8yo"/><path class="ie20z47df"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tissue-sample" /></template>
<style>
.cl777l8yo {
  d: path("M10.75 3.25c0-.75 2.5-.75 2.5 0m-2.5 0L7.5 14.5c-.25 1 .75 2.5 2.5 4m3.25-15.25L16.5 14.5c.25 1-.75 2.5-2.5 4M8.75 9.25l1.25.5m5.25-.5l-1.25.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie20z47df {
  fill: currentColor;
  d: path("M10.25 19.75c0-1.25 1-2 2-1.75c1.25.25 1.75 1.25 1.5 2.25s-1.25 1.5-2.25 1.25c-.75-.25-1.25-.75-1.25-1.75");
}

</style>

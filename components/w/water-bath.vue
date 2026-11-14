<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tt-ql0bjg"/><path class="r8lm80s3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-bath" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r8lm80s3k {
  d: path("M7.5 3v9a1.75 1.75 0 0 0 3.5 0V3m3 0v9a1.75 1.75 0 0 0 3.5 0V3M5.25 17.5q2.25-1.5 4.5 0t4.5 0t4.5 0");
}

.tt-ql0bjg {
  d: path("M2.5 9v10A2.5 2.5 0 0 0 5 21.5h14a2.5 2.5 0 0 0 2.5-2.5V9");
}

</style>

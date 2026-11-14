<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r13b0mb9d"/><path class="namg8su1t"/><path class="nzi44zb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ventilator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.namg8su1t {
  d: path("M5.25 7.25H7L8 5l1.5 4.5l1-2.25h2.25M4.5 21h.01m8.99 0h.01M15 4.5c4 0 5.75 2.5 5.75 6v11");
}

.nzi44zb9o {
  d: path("M15 7.75c1.75 0 2.75 1.25 2.75 2.75v11m0-7.5h3m-3 4h3");
}

.r13b0mb9d {
  d: path("M6.5 2.5h5A3.5 3.5 0 0 1 15 6v2a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 3 8V6a3.5 3.5 0 0 1 3.5-3.5m2.5 9V19m-4.5 0h9");
}

</style>

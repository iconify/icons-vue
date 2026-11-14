<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fe-1y4_1b"/><path class="bwz-puxhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recycle-bag" /></template>
<style>
.bwz-puxhk {
  d: path("m9 16.5l2.25-3.75M10 13l1.25-.25l.25 1.25m1.25-1.25L15 16.5m.25-1.25L15 16.5l-1.25-.25m.5 1.25h-4.5m1-1l-1 1l1 1");
}

.fe-1y4_1b {
  d: path("M5.879 7h12.242a1.75 1.75 0 0 1 1.745 1.875l-.75 10.5A1.75 1.75 0 0 1 17.371 21H6.629a1.75 1.75 0 0 1-1.745-1.625l-.75-10.5A1.75 1.75 0 0 1 5.879 7M8.5 7a3.5 3.5 0 0 1 7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

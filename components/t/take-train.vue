<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yju2pkoov"/><path class="vhym6jb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:take-train" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhym6jb3w {
  d: path("M7.25 8h1.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 5.5 9.75A1.75 1.75 0 0 1 7.25 8m8 0h1.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 15.25 8M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.5 20h19");
}

.yju2pkoov {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 5");
}

</style>

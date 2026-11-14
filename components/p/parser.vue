<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h0u6ym_ts"/><path class="pjlvoibdz"/><path class="z5srf6byj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parser" /></template>
<style>
.h0u6ym_ts {
  d: path("M8 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5 10V8.25h10V10m-5-3.5v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pjlvoibdz {
  d: path("M3 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2 5.5v-1.75h8v1.75M15 14v1.75");
}

.z5srf6byj {
  d: path("M9 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>

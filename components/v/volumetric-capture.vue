<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdz4b9b2t"/><path class="zs3mm-brs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volumetric-capture" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdz4b9b2t {
  d: path("M7 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M4 19c0-3.25 2.75-5.5 6.5-5.5c1.012 0 1.941.167 2.756.478");
}

.zs3mm-brs {
  d: path("M3 6.5a7.5 2.25 0 1 0 15 0a7.5 2.25 0 1 0-15 0M15.75 16h2a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 17.75 21h-2A1.75 1.75 0 0 1 14 19.25v-1.5A1.75 1.75 0 0 1 15.75 16m3.75 1.5L22 16v5l-2.5-1.5");
}

</style>

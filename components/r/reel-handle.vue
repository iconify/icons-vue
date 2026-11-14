<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrtakbcss"/><path class="cx1ksjbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reel-handle" /></template>
<style>
.cx1ksjbat {
  d: path("M8 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrtakbcss {
  d: path("M2.5 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m9-1.5L18 6m-.5-1a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10 6.5v-3m-4 0h8");
}

</style>

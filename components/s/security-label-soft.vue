<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sb0of0uav"/><path class="g7phdfnuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-label-soft" /></template>
<style>
.g7phdfnuj {
  d: path("M21.5 16h-4a1.5 1.5 0 0 0-1.5 1.5v4M6 15V6h9v7H9V9h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sb0of0uav {
  d: path("M2.5 4.5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2V16L16 21.5H4.5a2 2 0 0 1-2-2Z");
}

</style>

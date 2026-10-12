<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f0qzv3b8g"/><path class="m2hlpv2fy"/><circle class="pvmwfbkfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-cutter" /></template>
<style>
.f0qzv3b8g {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 12.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2hlpv2fy {
  d: path("M6 16.75h12m-13-4l9.76-6.85");
}

.pvmwfbkfk {
  cx: 16.4px;
  cy: 4.75px;
  r: 2px;
}

</style>

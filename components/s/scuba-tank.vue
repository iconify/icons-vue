<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b35c6vbgg"/><path class="m0sztr06d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scuba-tank" /></template>
<style>
.b35c6vbgg {
  width: 8px;
  height: 14.25px;
  x: 8px;
  y: 7px;
  rx: 3.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0sztr06d {
  d: path("M8 11h8m-8 6.25h8M10.75 7V4.25h2.5V7Zm2.5-2.25h3.25A2.25 2.25 0 0 1 18.75 7v3");
}

</style>

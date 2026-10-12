<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kofq0tspe"/><path class="rcnhoqkjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zoom-lens" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kofq0tspe {
  width: 2.5px;
  height: 6px;
  x: 2.75px;
  y: 6.75px;
  rx: 1px;
}

.rcnhoqkjj {
  d: path("M6.5 4.75h6.25q1.25 0 1.25.75t1.25.75H20q1.25 0 1.25 1.25V12q0 1.25-1.25 1.25h-4.75Q14 13.25 14 14t-1.25.75H6.5q-1.25 0-1.25-1.25V6q0-1.25 1.25-1.25m3 0v10M6.5 18h11M8 16.5L6.5 18L8 19.5m8-3l1.5 1.5l-1.5 1.5");
}

</style>

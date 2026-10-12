<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr0doac5x"/><circle class="ev5lzbc3d"/><path class="h-aeuf0rh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visiting-card" /></template>
<style>
.ev5lzbc3d {
  cx: 8.75px;
  cy: 9.5px;
  r: 1.75px;
}

.h-aeuf0rh {
  d: path("M12.25 8.5h4m-4 2.75h4M5 14.5h14q1.25 0 1.43 1.24l.64 4.27q.18 1.24-1.07 1.24H4q-1.25 0-1.07-1.24l.64-4.27Q3.75 14.5 5 14.5M7 18h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr0doac5x {
  d: path("M4.75 14.5V6.75a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v7.75Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mczfo2bdk"/><path class="a__52mbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:synthetic-data" /></template>
<style>
.a__52mbfh {
  d: path("M2.75 7h12.5m-12.5 4h12.5m-8-4v8.25m10.75-.5q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mczfo2bdk {
  width: 12.5px;
  height: 12.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.25px;
}

</style>

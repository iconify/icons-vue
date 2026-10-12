<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="kdxq9hffu"/><rect class="vx1tf140i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spacesuit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdxq9hffu {
  d: path("M8 10.25h8q1 0 1.57.82l2.36 3.36q.57.82-.24 1.4l-.13.09q-.81.58-1.41-.22l-1.05-1.4q-.6-.8-.6.2v5.75q0 1-1 1h-1.75q-1 0-1.22-.97l-.31-1.31q-.22-.97-.44 0l-.31 1.31q-.22.97-1.22.97H8.5q-1 0-1-1V14.5q0-1-.6-.2l-1.05 1.4q-.6.8-1.41.22l-.13-.09q-.81-.58-.24-1.4l2.36-3.36Q7 10.25 8 10.25");
}

.vx1tf140i {
  width: 4px;
  height: 2.5px;
  x: 10px;
  y: 13px;
  rx: 0.5px;
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>

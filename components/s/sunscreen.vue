<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crefs-rjf"/><rect class="mx160tx5b"/><circle class="zoz2euh6v"/><path class="gtcrd1b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunscreen" /></template>
<style>
.crefs-rjf {
  d: path("M4 2.75h6.5q1.25 0 1.13 1.24l-1.01 11.02q-.12 1.24-1.37 1.24h-4q-1.25 0-1.37-1.24L2.87 3.99Q2.75 2.75 4 2.75");
}

.gtcrd1b4v {
  d: path("M17 3v1m0 6.5v1m3.25-4.25h1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mx160tx5b {
  width: 5px;
  height: 5px;
  x: 4.75px;
  y: 16.25px;
  rx: 1px;
}

.zoz2euh6v {
  cx: 17px;
  cy: 7.25px;
  r: 1.75px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m2fv_0jwv"/><rect class="f3dawcb_y"/><path class="n6b-3w5yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sugarcane" /></template>
<style>
.f3dawcb_y {
  width: 3.5px;
  height: 18.5px;
  x: 14.5px;
  y: 2.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2fv_0jwv {
  width: 3.5px;
  height: 16.75px;
  x: 6px;
  y: 4.5px;
  rx: 1.5px;
}

.n6b-3w5yt {
  d: path("M6 9h3.5M6 13.75h3.5M6 18h3.5m5-10.5H18m-3.5 4.75H18M14.5 17H18M6 9C4 8 3 6.5 2.75 4.5M18 12.25c1.75-.25 2.75-1.5 3.25-3.5m-11.75 5c2 0 3.5.75 5 2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f65050bll"/><rect class="g8s4mo40r"/><path class="y7367rsff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:site-office" /></template>
<style>
.f65050bll {
  width: 14.5px;
  height: 7.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.25px;
}

.g8s4mo40r {
  width: 14.5px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7367rsff {
  d: path("M6 5.25h2.25q.5 0 .5.5v1.5q0 .5-.5.5H6q-.5 0-.5-.5v-1.5q0-.5.5-.5m5.75 0H14q.5 0 .5.5v1.5q0 .5-.5.5h-2.25q-.5 0-.5-.5v-1.5q0-.5.5-.5M6 16h2.5q.5 0 .5.5V18q0 .5-.5.5H6q-.5 0-.5-.5v-1.5q0-.5.5-.5m5.75 5.25V16h2.75v5.25m2.75-11h1.25l2.75 11");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="juo8wy96b"/><path class="x59waabjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turtleneck" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.juo8wy96b {
  width: 6px;
  height: 5.75px;
  x: 9px;
  y: 2.75px;
  rx: 1.25px;
}

.x59waabjq {
  d: path("M9 5.6h6M9.75 8.5h4.5q1.25 0 2.38.53l1.99.94q1.13.53 1.32 1.77l1.12 7.27q.19 1.24-1.03 1.5l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23q-1.22-.26-1.03-1.5l1.12-7.27q.19-1.24 1.32-1.77l1.99-.94Q8.5 8.5 9.75 8.5m-3 4.5v8m10.5-8v8");
}

</style>

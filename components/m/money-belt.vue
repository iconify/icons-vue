<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pcbwoedwa"/><rect class="g0mrh1avi"/><path class="u-gl1_w4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:money-belt" /></template>
<style>
.g0mrh1avi {
  width: 12px;
  height: 7.5px;
  x: 6px;
  y: 9px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcbwoedwa {
  d: path("M6 12.75q-1.75-.25-3.25-1.5M18 12.75q1.75-.25 3.25-1.5");
}

.u-gl1_w4y {
  d: path("M8.5 11.75h7m0 0v2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wy-87fpug"/><circle class="krrzio5fu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:top-p-slider" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krrzio5fu {
  cx: 18px;
  cy: 9px;
  r: 1.75px;
}

.wy-87fpug {
  d: path("M4 5.75v15.5m4-11.5v11.5m4-7v7m6-18.5v4.5m0 3.5v10.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnc4uibjx"/><path class="vohe0zb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:manor-house" /></template>
<style>
.bnc4uibjx {
  d: path("m3.63 10.475l7.25-6.041a1.75 1.75 0 0 1 2.24 0l7.25 6.041A1.75 1.75 0 0 1 21 11.82v7.43A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25v-7.43a1.75 1.75 0 0 1 .63-1.345m.87-.725V4h3v3.25m9 0V4h3v5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vohe0zb5y {
  d: path("M10 21v-4a2 2 0 0 1 4 0v4");
}

</style>

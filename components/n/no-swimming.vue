<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ys7yyt9fo"/><path class="hr7-yt4kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-swimming" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr7-yt4kf {
  d: path("m7.25 13l5.5 3.25M9.5 14.33L8.5 12m-5 8c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1M3.75 3.75l16.5 16.5");
}

.ys7yyt9fo {
  cx: 5px;
  cy: 11px;
  r: 1.5px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="epklwpbwu"/><path class="rmger2usj"/><circle class="znr0jubqw"/><path class="joijmw2ee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:screen-magnifier" /></template>
<style>
.epklwpbwu {
  width: 12px;
  height: 9.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.joijmw2ee {
  d: path("m19.45 18.45l1.8 1.8m-5-3.75h2.5m-1.25-1.25v2.5");
}

.rmger2usj {
  d: path("M8.75 13.25v3.5m-3 0h6");
}

.znr0jubqw {
  cx: 17.5px;
  cy: 16.5px;
  r: 2.75px;
}

</style>

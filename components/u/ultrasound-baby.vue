<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr1al8b7d"/><circle class="qxcmxt8oh"/><path class="wnme80yll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ultrasound-baby" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qxcmxt8oh {
  cx: 11px;
  cy: 10px;
  r: 1.75px;
}

.wnme80yll {
  d: path("M12.25 11.25a2.5 2.5 0 0 1-.5 4.5a1 1 0 0 1-.25-2a.75.75 0 0 0 .25-1.25Z");
}

.xr1al8b7d {
  d: path("M11.13 20.4L3.6 8.1a1 1 0 0 1 .35-1.4a16 16 0 0 1 16.1 0a1 1 0 0 1 .35 1.4l-7.53 12.3a1 1 0 0 1-1.74 0");
}

</style>

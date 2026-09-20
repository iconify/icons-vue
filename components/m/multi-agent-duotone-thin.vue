<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ad2vcjg0g"/><path class="v5565pevr"/><path class="arm3v4biy"/><path class="wxv870p2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-agent-duotone-thin" /></template>
<style>
.ad2vcjg0g {
  fill: currentColor;
  d: path("M9.9 3.92a4.5 4.5 0 1 1 -3.8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.arm3v4biy {
  d: path("M9.9 3.92a4.5 4.5 0 1 1 -3.8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5565pevr {
  fill: currentColor;
  d: path("M17.9 11.92a4.5 4.5 0 1 1 -3.8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wxv870p2c {
  d: path("M17.9 11.92a4.5 4.5 0 1 1 -3.8 0");
}

</style>

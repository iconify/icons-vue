<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="v4lpui97q"/><path class="ijs0p36kx"/><rect class="lyp7ak-rs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:separator-line" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijs0p36kx {
  d: path("M2.75 12h18.5");
}

.lyp7ak-rs {
  width: 14.5px;
  height: 6px;
  x: 4.75px;
  y: 15.25px;
  rx: 2px;
}

.v4lpui97q {
  width: 14.5px;
  height: 6px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>

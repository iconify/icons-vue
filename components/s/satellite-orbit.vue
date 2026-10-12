<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="aqhok2bbj"/><path class="moekz8btc"/><path class="aazdi0b7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:satellite-orbit" /></template>
<style>
.aazdi0b7u {
  d: path("m17.17 3.21l2.64 1.43l-1.42 2.64l-2.64-1.43Z");
}

.aqhok2bbj {
  cx: 12px;
  cy: 12px;
  r: 4px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moekz8btc {
  d: path("M19.02 6.13a9.25 7-30 1 1-2.64-1.45");
}

</style>

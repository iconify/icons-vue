<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="azlmfgbpz"/><path class="zcniayi6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-camp" /></template>
<style>
.azlmfgbpz {
  d: path("M2.5 11L12 3.5l9.5 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zcniayi6o {
  d: path("M15.5 6.25V3H18v5.25M5 9v11.5M19 9v11.5m-17 0h20M11.5 14h1a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 19v-3.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>

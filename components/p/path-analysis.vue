<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qujm8kb3g"/><path class="h5x-nubbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:path-analysis" /></template>
<style>
.h5x-nubbj {
  d: path("M5.5 12c2.5 0 3-4.5 5.5-4.5M5.5 12c2.5 0 3 4.5 5.5 4.5m0-9c3.5 0 4-3 7.5-3m-7.5 3c3.5 0 4 2.5 7.5 2.5M11 16.5c3.5 0 4-2.5 7.5-2.5M11 16.5c3.5 0 4 3 7.5 3m.25-15a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 5.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 5.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qujm8kb3g {
  fill: currentColor;
  d: path("M2 12a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 2 12");
}

</style>

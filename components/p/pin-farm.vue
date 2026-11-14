<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyg8a9-7o"/><path class="c_svpacie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-farm" /></template>
<style>
.c_svpacie {
  d: path("M9.5 12.5h5A1.5 1.5 0 0 1 16 14v5.5a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 19.5V14a1.5 1.5 0 0 1 1.5-1.5m-1.5 0l8 8.5m0-8.5L8 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yyg8a9-7o {
  d: path("M3.5 21V10.5l3-5L12 3l5.5 2.5l3 5V21Z");
}

</style>

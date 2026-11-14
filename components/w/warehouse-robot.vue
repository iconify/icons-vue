<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-afzc_rg"/><path class="mznzcabmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warehouse-robot" /></template>
<style>
.e-afzc_rg {
  d: path("M10.375 9h3.25A4.375 4.375 0 0 1 18 13.375v.25A4.375 4.375 0 0 1 13.625 18h-3.25A4.375 4.375 0 0 1 6 13.625v-.25A4.375 4.375 0 0 1 10.375 9M12 9V5.5m0-1h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mznzcabmn {
  d: path("M8.5 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0M7 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a3mi72b6w"/><path class="yjm2_wbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-dab" /></template>
<style>
.a3mi72b6w {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-5.5A3.5 3.5 0 0 1 6 8m.5 0l9-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjm2_wbis {
  d: path("M5 14.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M14 11h3a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 17 14h-3a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 14 11m-1.5 6h6");
}

</style>

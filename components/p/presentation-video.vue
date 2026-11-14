<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxegrf_dd"/><path class="beeuukb-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-video" /></template>
<style>
.beeuukb-v {
  d: path("m11.75 6.798l1.998 1.153a1.5 1.5 0 0 1 0 2.598l-1.998 1.153a1.5 1.5 0 0 1-2.25-1.299V8.097a1.5 1.5 0 0 1 2.25-1.299");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxegrf_dd {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v6.5A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 6 2.5m1 19L9 16m8 5.5L15 16");
}

</style>

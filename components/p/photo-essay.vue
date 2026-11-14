<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrqpygbiq"/><path class="wj22xub1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:photo-essay" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrqpygbiq {
  d: path("M5.125 2.5h6.75A2.625 2.625 0 0 1 14.5 5.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 2.5 8.875v-3.75A2.625 2.625 0 0 1 5.125 2.5m7 12h6.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 9.5 18.875v-1.75a2.625 2.625 0 0 1 2.625-2.625");
}

.wj22xub1h {
  d: path("M5 11.5L8.5 7l3.5 4.5m0 10l3.5-4l3.5 4M14.5 7H18v7.5");
}

</style>

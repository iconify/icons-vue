<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wc23aqbga"/><path class="ev5ytue4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:temperature-chart" /></template>
<style>
.ev5ytue4h {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-2.25 13v-3a1.5 1.5 0 0 1 3 0v3a2.5 2.5 0 1 1-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc23aqbga {
  d: path("M3.5 3v17.5H13");
}

</style>

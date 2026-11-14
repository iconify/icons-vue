<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gpx7f9big"/><path class="ekvh6kq5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:propagator" /></template>
<style>
.ekvh6kq5l {
  d: path("M9 15v-3.5M7.5 10L9 11.5l1.5-1.5m4.5 5v-3.5M13.5 10l1.5 1.5l1.5-1.5");
}

.gpx7f9big {
  d: path("M3 15h18v3.5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm1 0C4 8 8 4.5 12 4.5S20 8 20 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

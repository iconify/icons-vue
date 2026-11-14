<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i43y08ysb"/><path class="va1r92bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:portable-compressor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i43y08ysb {
  d: path("M6 7.5h6a3.5 3.5 0 0 1 3.5 3.5v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-6A3.5 3.5 0 0 1 6 7.5m0 0v-3h6v3m3.5 8.5c6 0 6-6.5 3-6.5");
}

.va1r92bom {
  d: path("M5.75 14a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M9 14l1.5-1.5");
}

</style>

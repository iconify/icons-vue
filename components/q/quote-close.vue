<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uq8e8kbmv"/><path class="pt6m92hss"/><path class="n0f5nlbtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:quote-close" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0f5nlbtw {
  d: path("M20.25 8.5c0 4.5-2 7.5-5.75 9");
}

.pt6m92hss {
  d: path("M10.25 8.5c0 4.5-2 7.5-5.75 9m9.25-9a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.uq8e8kbmv {
  d: path("M3.75 8.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>

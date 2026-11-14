<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skuayb02t"/><path class="ymg97l6nr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-filter-tap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.skuayb02t {
  d: path("M4 21.5h6m-3 0V8a5 5 0 0 1 10 0v1.5");
}

.ymg97l6nr {
  d: path("M17 9.5za2.5 2.5 0 0 1 2.5 2.5v1.5A2.5 2.5 0 0 1 17 16a2.5 2.5 0 0 1-2.5-2.5V12A2.5 2.5 0 0 1 17 9.5");
}

</style>

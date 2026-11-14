<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xmumt86wb"/><path class="x8fcfss3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-reduced" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8fcfss3c {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 15v6m-2.5-2.5L18 21l2.5-2.5");
}

.xmumt86wb {
  d: path("M4.5 3h7l9.5 9.5l-1 1h-5.75a2 2 0 0 0-2 2v5l-.75.5L3 11.5v-7A1.5 1.5 0 0 1 4.5 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wtwrxlbwk"/><path class="oil_6pbfc"/><path class="a2z5i_nhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-stand-wheels" /></template>
<style>
.a2z5i_nhx {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oil_6pbfc {
  d: path("M4.75 12.5h14.5A1.75 1.75 0 0 1 21 14.25A1.75 1.75 0 0 1 19.25 16H4.75A1.75 1.75 0 0 1 3 14.25a1.75 1.75 0 0 1 1.75-1.75");
}

.wtwrxlbwk {
  d: path("M9.271 5h5.458a1.5 1.5 0 0 1 1.48 1.747l-.75 4.5a1.5 1.5 0 0 1-1.48 1.253h-3.958a1.5 1.5 0 0 1-1.48-1.253l-.75-4.5A1.5 1.5 0 0 1 9.271 5");
}

</style>

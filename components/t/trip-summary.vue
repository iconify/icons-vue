<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re3nbbcdl"/><path class="yms1g_6ir"/><path class="h5mtstz0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trip-summary" /></template>
<style>
.h5mtstz0v {
  d: path("M12 18c-2.5-2.5-3.75-4.5-3.75-6.75a3.75 3.75 0 0 1 7.5 0c0 2.25-1.25 4.25-3.75 6.75m0-6.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.re3nbbcdl {
  d: path("M8.5 5v-.5A1.5 1.5 0 0 1 10 3h4a1.5 1.5 0 0 1 1.5 1.5V5h2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

.yms1g_6ir {
  d: path("M10.75 3h2.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-2.5A2.25 2.25 0 0 1 8.5 5.25A2.25 2.25 0 0 1 10.75 3");
}

</style>

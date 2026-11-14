<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmeiyr_ni"/><path class="yfwi44_6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tax-car" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmeiyr_ni {
  d: path("M2.5 10V7.5l2.5-1L7.5 3H13l2.5 3.5l3 1V10Z");
}

.yfwi44_6l {
  d: path("M4.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m3 9.5l6-6m-5 1h.01m3.99 4h.01");
}

</style>

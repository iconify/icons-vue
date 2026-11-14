<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kejk8vbou"/><path class="k78_w23mm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mesh-node-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k78_w23mm {
  d: path("M5.75 9.25a8.84 8.84 0 0 1 12.5 0M8 11.5a5.66 5.66 0 0 1 8 0m-4 4h.01m2.74 2.5l2 2L21 15.75");
}

.kejk8vbou {
  d: path("M3.5 7a12 12 0 0 1 17 0");
}

</style>

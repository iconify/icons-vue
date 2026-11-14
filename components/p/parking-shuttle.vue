<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvi0xt4dm"/><path class="i7mt9kacc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-shuttle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7mt9kacc {
  d: path("M5.5 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m10 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0-12v6h6M6 13V7.75h1.75a1.75 1.75 0 0 1 0 3.5H6");
}

.tvi0xt4dm {
  d: path("M2.5 16.5V7a2 2 0 0 1 2-2h11l6 6v5.5h-1.75a2.75 2.75 0 0 0-5.5 0h-4.5a2.75 2.75 0 0 0-5.5 0Z");
}

</style>

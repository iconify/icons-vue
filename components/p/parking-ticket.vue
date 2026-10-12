<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="apfkwridv"/><path class="pai9l_1nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parking-ticket" /></template>
<style>
.apfkwridv {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pai9l_1nu {
  d: path("M8.75 6h6.5m-6.5 12.25h6.5M10.5 15.5V9.25h2a2 2 0 0 1 0 4h-2");
}

</style>

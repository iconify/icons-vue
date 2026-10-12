<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kd70e7blo"/><path class="arihkvbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:male-male-symbol" /></template>
<style>
.arihkvbce {
  d: path("M11.4 12.25a4 4 0 1 1 0 8a4 4 0 1 1 0-8m2.83 1.17L18 9.65m-2.75 0H18v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kd70e7blo {
  d: path("M8.75 7.25a4 4 0 1 1 0 8a4 4 0 1 1 0-8m2.83 1.17L16 4m-2.75 0H16v2.75");
}

</style>

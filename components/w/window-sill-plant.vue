<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0mom9hao"/><path class="qtyjmzxew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-sill-plant" /></template>
<style>
.a0mom9hao {
  d: path("M5 20V5.5A1.5 1.5 0 0 1 6.5 4h11A1.5 1.5 0 0 1 19 5.5V20M3 20h18M5 7.5h14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qtyjmzxew {
  d: path("M9.5 15.5h5L14 20h-4Zm2.5 0V12m0 1.5q-3 0-3.5-3q3 0 3.5 3m0-1q3 0 3.5-2q-3-.5-3.5 2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jflqnibxz"/><path class="yjxl-8b4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vram" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jflqnibxz {
  d: path("M6 5.5h12A3.5 3.5 0 0 1 21.5 9v4.5A3.5 3.5 0 0 1 18 17H6a3.5 3.5 0 0 1-3.5-3.5V9A3.5 3.5 0 0 1 6 5.5M6 17v3.5M9.5 17v3.5M13 17v3.5m3.5-3.5v3.5");
}

.yjxl-8b4y {
  d: path("M7 8.5h.5A1.5 1.5 0 0 1 9 10v2a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 12v-2A1.5 1.5 0 0 1 7 8.5m4.75 0h.5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5m4.75 0h.5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-.5A1.5 1.5 0 0 1 15 12v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>

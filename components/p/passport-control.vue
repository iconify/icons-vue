<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ithhcbw_s"/><path class="y2rth1byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-control" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ithhcbw_s {
  d: path("M12.25 21.25h-5.5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2h9.5a2 2 0 0 1 2 2v7.5");
}

.y2rth1byv {
  d: path("M8.25 9.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m0 0h6.5M8.25 16h3m3.5 1.75l1.75 1.75l3.5-3.75");
}

</style>

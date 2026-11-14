<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfy9dabqr"/><path class="gb26_k93p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:media-query" /></template>
<style>
.gb26_k93p {
  d: path("m8.5 8.25l-2 2l2 2m7-4l2 2l-2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfy9dabqr {
  d: path("M5.5 3.5h13A3.5 3.5 0 0 1 22 7v6.5a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 13.5V7a3.5 3.5 0 0 1 3.5-3.5M12 17v3.5m-4 0h8M6.5 10.25h11");
}

</style>

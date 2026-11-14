<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yajb1wbnn"/><path class="zj6j2_b3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-dive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yajb1wbnn {
  d: path("M5 7h10.5A2.5 2.5 0 0 1 18 9.5V13a3 3 0 0 1-3 3h-2l-1.25-2h-3L7.5 16h-2a3 3 0 0 1-3-3V9.5A2.5 2.5 0 0 1 5 7m5.25 0v7");
}

.zj6j2_b3v {
  d: path("M21 3.5V16a3 3 0 0 1-3 3h-3");
}

</style>

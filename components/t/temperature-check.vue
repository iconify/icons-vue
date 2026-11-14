<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7_-2rb4f"/><path class="dt5ew-iwf"/><path class="wpuqwc-ux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:temperature-check" /></template>
<style>
.dt5ew-iwf {
  d: path("M21.152 2.848za1.25 1.25 0 0 1 0 1.768l-3.536 3.536a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l3.536-3.536a1.25 1.25 0 0 1 1.768 0");
}

.g7_-2rb4f {
  d: path("M7 21.5V18c-2-1.5-2.75-3.5-2.75-5.75c0-3.75 2.75-6.5 6.25-6.5s6 2.25 6 5.75l1.25 3q.375.75-.75.75h-.5v2c0 1-.75 1.75-1.75 1.75H13v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpuqwc-ux {
  fill: currentColor;
  d: path("M14.5 8.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8uaqubzp"/><path class="yoy8brx5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-location" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8uaqubzp {
  d: path("M12 15.5s-5-4-5-8a5 5 0 0 1 10 0c0 4-5 8-5 8");
}

.yoy8brx5p {
  d: path("M10.25 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M3.375 19l.59-1.012a1.5 1.5 0 0 1 .821-.667l3.117-1.039a2 2 0 0 1 .198-.051l3.597-.674a1.5 1.5 0 0 1 .602.01l4.043.898a1.5 1.5 0 0 1 .303.102l2.736 1.263a1.5 1.5 0 0 1 .6.502l.643.918a.794.794 0 0 1-.651 1.25H4.237a.997.997 0 0 1-.862-1.5M8.5 20.5l1-1.75m6 1.75l-1-1.75");
}

</style>

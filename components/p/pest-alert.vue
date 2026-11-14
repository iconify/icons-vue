<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fy9z8quni"/><path class="g6_mk0ppv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pest-alert" /></template>
<style>
.fy9z8quni {
  d: path("M4.75 13.25a3.75 4.5 0 1 0 7.5 0a3.75 4.5 0 1 0-7.5 0");
}

.g6_mk0ppv {
  d: path("M6.75 9a1.75 1.75 0 0 1 3.5 0m-1.75.5v8.25M4.5 12l-2-1.25M12.25 12l2-1.25m-9.75 4l-2 1m9.75-1l2 1m-7-8L6.25 6M9.5 7.75l1-1.75M20 5v8.5m0 4.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

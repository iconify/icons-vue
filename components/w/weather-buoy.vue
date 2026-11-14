<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="maxbprbxu"/><path class="z0lkabbev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weather-buoy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.maxbprbxu {
  d: path("M6.5 15a5.5 5.5 0 0 1 11 0");
}

.z0lkabbev {
  d: path("M2.5 15q2-1.5 4 0h11q2 1.5 4 0M12 9.5V3M2.5 19.5q2.375-1.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>

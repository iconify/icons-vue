<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5k-6-2wb"/><path class="cimg-_mvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-mode" /></template>
<style>
.cimg-_mvy {
  d: path("M10.75 7.75L12 9l1.25-1.25m-2.5 8.5L12 15l1.25 1.25m3.056-3.208l-1.708.458l.458 1.708M8.944 8.792l.458 1.708l-1.708.458m1.25 4.25l.458-1.708l-1.708-.458m8.612-2.084l-1.708-.458l.458-1.708");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5k-6-2wb {
  d: path("M9.625 3.5h4.75A6.125 6.125 0 0 1 20.5 9.625v4.75a6.125 6.125 0 0 1-6.125 6.125h-4.75A6.125 6.125 0 0 1 3.5 14.375v-4.75A6.125 6.125 0 0 1 9.625 3.5M12 7v10m4.33-7.5l-8.66 5m8.66 0l-8.66-5");
}

</style>

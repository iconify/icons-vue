<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1eb__bjk"/><path class="w4u6l0b4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shift-schedule" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1eb__bjk {
  d: path("M5.125 7.5h3.25A2.625 2.625 0 0 1 11 10.125v3.75A2.625 2.625 0 0 1 8.375 16.5h-3.25A2.625 2.625 0 0 1 2.5 13.875v-3.75A2.625 2.625 0 0 1 5.125 7.5m10.5 0h3.25a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 13 13.875v-3.75A2.625 2.625 0 0 1 15.625 7.5");
}

.w4u6l0b4z {
  d: path("M5 12a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 5 12m1.75-3.25v.5m0 5.5v.5m-3-3.25h.5m5 0h.5M18 9.5c-2 .5-2.75 3-1.75 4.5s3 1.75 4 .5c-1.75-.25-3-2.75-2.25-5");
}

</style>

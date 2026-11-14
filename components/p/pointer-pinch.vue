<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p09n38ugn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pointer-pinch" /></template>
<style>
.p09n38ugn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 14.5v-6a1.5 1.5 0 0 1 3 0v-1a1.5 1.5 0 0 1 3 0V13a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0v3.5c0 2.9-1.75 5-4.5 5h-1.5c-1.6 0-2.75-.6-3.5-1.75l-4.25-5a1.5 1.5 0 0 1 2-2Zm3-6V12m-8-8H6M4.5 2.5L6 4L4.5 5.5m17-1.5H18m1.5-1.5L18 4l1.5 1.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w9mhs8b7b"/><path class="j87w5x4jr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stopwatch-stop" /></template>
<style>
.j87w5x4jr {
  fill: currentColor;
  d: path("M8.75 10h6.5v6.5h-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9mhs8b7b {
  d: path("M3.75 13.25a8.25 8.25 0 1 0 16.5 0a8.25 8.25 0 1 0-16.5 0ZM12 2.5V5M9.5 2.5h5");
}

</style>

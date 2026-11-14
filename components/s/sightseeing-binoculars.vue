<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z789a247t"/><path class="i-ew4jjjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sightseeing-binoculars" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-ew4jjjn {
  d: path("M7 10.5L8.5 5H10m7 5.5L15.5 5H14m-4 0h4");
}

.z789a247t {
  d: path("M3 14.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>

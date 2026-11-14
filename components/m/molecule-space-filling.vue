<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g32b4l5lz"/><path class="c3qc_xvjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:molecule-space-filling" /></template>
<style>
.c3qc_xvjh {
  d: path("M7 12.25a4 4 0 1 1 5-5m3 1a3 3 0 1 1 2 4m-9 3a2.5 2.5 0 1 0 4 2");
}

.g32b4l5lz {
  d: path("M7 12.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy8o3rb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:progress-pause" /></template>
<style>
.oy8o3rb8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8h2a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-2a4 4 0 0 1-4-4a4 4 0 0 1 4-4m-1 4h4m7-2.5v5m3.5-5v5");
}

</style>

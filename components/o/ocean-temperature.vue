<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgjndy85o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ocean-temperature" /></template>
<style>
.mgjndy85o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 13.5V5.25a2.75 2.75 0 0 1 5.5 0v8.25a4.5 4.5 0 1 1-5.5 0M8.5 8v9.25m7.25-.75q1.5-1.5 3 0t3 0m-6 3.5q1.5-1.5 3 0t3 0");
}

</style>

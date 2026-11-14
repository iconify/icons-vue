<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyubgq8-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measure-temperature" /></template>
<style>
.hyubgq8-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 12.5V5.25a2.75 2.75 0 0 1 5.5 0v7.25a4.5 4.5 0 1 1-5.5 0M8 7v9m8.5 4.5q-1.25-1.75 0-3.5t0-3.5m3.5 7q-1.25-1.75 0-3.5t0-3.5");
}

</style>

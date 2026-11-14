<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tix-u0b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:molecule-model" /></template>
<style>
.tix-u0b1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0M3 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m13 1a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M15.75 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-6.5-8.25L6.25 7m7 4l3.25-2.75M13.25 15l3 2.75");
}

</style>

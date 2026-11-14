<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff7s9lbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:particle-collision" /></template>
<style>
.ff7s9lbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12A2.25 2.25 0 1 0 7 12a2.25 2.25 0 1 0-4.5 0M17 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-5-3V6.5m0 8.5v2.5m2.25-7.75L16 8M9.75 9.75L8 8m6.25 6.25L16 16m-6.25-1.75L8 16");
}

</style>

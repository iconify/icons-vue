<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esink1b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mobility-scooter" /></template>
<style>
.esink1b0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 18a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m12 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m-6.5 0h6.5m3.75-3l-3-8.5h-3M5 8.5h4a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 11.5H5A1.5 1.5 0 0 1 3.5 10A1.5 1.5 0 0 1 5 8.5m-1-4v4");
}

</style>

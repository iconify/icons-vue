<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwaikpdwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-temperature" /></template>
<style>
.cwaikpdwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.797 16h6.406a1.5 1.5 0 0 1 1.475 1.768l-.454 2.5a1.5 1.5 0 0 1-1.476 1.232H6.252a1.5 1.5 0 0 1-1.476-1.232l-.454-2.5A1.5 1.5 0 0 1 5.797 16M9 16v-6m0 3c-3 0-5.5-2-5.5-5.5C7 7.5 9 10 9 13m0-3c0-3.5 2.5-6.5 6-6.5C15 7 12.5 10 9 10m8.75 7v-2.5a1.25 1.25 0 0 1 2.5 0V17a2.5 2.5 0 1 1-2.5 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deuzvstov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-food-can" /></template>
<style>
.deuzvstov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5h15A1.5 1.5 0 0 1 21 6a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 6a1.5 1.5 0 0 1 1.5-1.5m0 3V18A1.5 1.5 0 0 0 6 19.5h12a1.5 1.5 0 0 0 1.5-1.5V7.5M4.5 11h15m-15 5h15");
}

</style>

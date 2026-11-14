<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxy173fmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seasonality" /></template>
<style>
.bxy173fmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 15c.75 0 1-6.5 3.25-6.5S7.75 15 8.5 15s1-6.5 3.25-6.5S14.25 15 15 15s1-6.5 3.25-6.5s2.5 6.5 3.25 6.5M2 6.25h3.5m2 0H11m2 0h3.5m2 0H22");
}

</style>

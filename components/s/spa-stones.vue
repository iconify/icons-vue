<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqcyfabmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spa-stones" /></template>
<style>
.tqcyfabmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.25a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0M6 10.75a6 2 0 1 0 12 0a6 2 0 1 0-12 0M3.5 18.5a8.5 2.75 0 1 0 17 0a8.5 2.75 0 1 0-17 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g68w-jbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maintenance-technician" /></template>
<style>
.g68w-jbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5h13m-11.5 0a5 5 0 0 1 10 0M7 7.5V9a3.5 3.5 0 0 0 7 0V7.5m-2.228 14.25H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.397 0 2.686.243 3.787.685m7.213.315a2.25 2.25 0 1 1-1.75-1.75m-2 3.75L15 21");
}

</style>

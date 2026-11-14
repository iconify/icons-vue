<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-rg7-jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sunset-trigger" /></template>
<style>
.ba-rg7-jm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 16a5 5 0 0 1 10 0m-12 0h10m-3-13.5v5M7.25 5.25L9.5 7.5l2.25-2.25m7 9.25l-3.5 4h2.5l-.5 3l3.5-4.25h-2.5Z");
}

</style>

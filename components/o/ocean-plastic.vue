<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymz8qvb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ocean-plastic" /></template>
<style>
.ymz8qvb3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3h2.5v2c1.4.6 2 1.6 2 2.9V12A1.25 1.25 0 0 1 14 13.25h-4A1.25 1.25 0 0 1 8.75 12V7.9c0-1.3.6-2.3 2-2.9Zm-8 13.5c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1m-18.48 4c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1");
}

</style>

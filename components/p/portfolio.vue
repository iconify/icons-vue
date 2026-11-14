<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gagmjkb0s"/><path class="apo-85o9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:portfolio" /></template>
<style>
.apo-85o9m {
  d: path("m6.5 16.5l3-3L12 15l5.5-4.5");
}

.gagmjkb0s {
  d: path("M3 7h18v13H3Zm6 0V5.5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

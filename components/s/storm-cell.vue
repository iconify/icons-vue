<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gc4hu6bwu"/><path class="rmycp3b0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:storm-cell" /></template>
<style>
.gc4hu6bwu {
  d: path("M20.25 9.75A8.5 8.5 0 1 1 18 6");
}

.rmycp3b0b {
  d: path("M15 6h3V3M8.5 15h7a2 2 0 0 0 .25-4A3.5 3.5 0 0 0 9 10.75A2.25 2.25 0 0 0 8.5 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

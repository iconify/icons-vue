<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0s6avbbh"/><path class="y10sszh8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-heatmap" /></template>
<style>
.h0s6avbbh {
  d: path("M13 21.5H2.5v-19h19v10.4M2.5 11H9m4-8.5v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y10sszh8j {
  d: path("M18 13.5c2.5 2 3.5 3.5 3.5 5a3.25 3.25 0 0 1-6.5 0c0-1.25.5-2 1.25-2.75c.25 1 .5 1.5 1 1.5q-.375-1.875.75-3.75Z");
}

</style>

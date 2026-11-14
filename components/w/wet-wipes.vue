<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cadbtsinr"/><path class="z8fc0ibgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wet-wipes" /></template>
<style>
.cadbtsinr {
  d: path("M9 8H6a3.5 3.5 0 0 0-3.5 3.5v5A3.5 3.5 0 0 0 6 20h12a3.5 3.5 0 0 0 3.5-3.5v-5A3.5 3.5 0 0 0 18 8h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8fc0ibgs {
  d: path("M9 13V8c0-2-1-3-.5-5q3.5 1 7 0c.5 2-.5 3-.5 5v5m-8.5 0h11");
}

</style>

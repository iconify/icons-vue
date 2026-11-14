<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azlmfgbpz"/><path class="oehlwebhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mine-camp" /></template>
<style>
.azlmfgbpz {
  d: path("M2.5 11L12 3.5l9.5 7.5");
}

.oehlwebhe {
  d: path("M15.5 6.25V3H18v5.25M5 9v11.5M19 9v11.5m-17 0h20M10 14h4v6.5h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ln635ebjn"/><path class="sdswmve2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ln635ebjn {
  d: path("m4.077 5.551l4.25-1.771a1.75 1.75 0 0 1 1.346 0l4.654 1.94a1.75 1.75 0 0 0 1.346 0l2.904-1.21A1.75 1.75 0 0 1 21 6.125V10.5a1.75 1.75 0 0 1-1.75 1.75H14A1.75 1.75 0 0 0 12.25 14v3.509a1.196 1.196 0 0 1-1.625 1.116l-.971-.373a1.75 1.75 0 0 0-1.301.018l-2.93 1.22A1.75 1.75 0 0 1 3 17.875V7.167a1.75 1.75 0 0 1 1.077-1.616M9 3.5V18m6-12v6.25");
}

.sdswmve2s {
  d: path("M15 17.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M19 19l1.75 1.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmetq5bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skirting-heater" /></template>
<style>
.nmetq5bri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h19v9h-19Zm4 2.75v3.5m3.5-3.5v3.5m3.5-3.5v3.5m3.5-3.5v3.5m-.5 10.75c-1.5-1.75 1.5-3.25 0-5m3.5 5c-1.5-1.75 1.5-3.25 0-5");
}

</style>

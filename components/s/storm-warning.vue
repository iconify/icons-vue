<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlbxlbbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:storm-warning" /></template>
<style>
.xlbxlbbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11a3 3 0 0 1 0-6a4.25 4.25 0 0 1 8.25.75A2.75 2.75 0 0 1 13 11Zm5 2.75L6.5 18h3l-1 3.5l4.5-5h-2.75ZM20 4v10m0 4.25h.01");
}

</style>

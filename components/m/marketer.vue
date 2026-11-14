<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcpycab8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marketer" /></template>
<style>
.mcpycab8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM2.5 21c0-3.5 2.25-6 4.75-6c2 0 3.75 1 4.75 2.5M13.5 8L18 5.5v8L13.5 11Zm2 3.75v3.75m5-8.25a3.25 3.25 0 0 1 0 4.5");
}

</style>

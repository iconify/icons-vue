<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv6-u7-nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:polar-vortex" /></template>
<style>
.sv6-u7-nc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12a6.5 6.5 0 0 1 13 0a8 8 0 0 1-16 0a9.5 9.5 0 0 1 16.25-6.75M13 8.75v6.5m-2.75-5l5.5 3.5m-5.5 0l5.5-3.5");
}

</style>

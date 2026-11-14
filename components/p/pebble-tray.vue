<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pezpr4bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pebble-tray" /></template>
<style>
.pezpr4bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.75h19l-2 6.25h-15Zm1.5 0a3 3 0 0 1 6 0m0 0a3.5 3.5 0 0 1 7 0m0 0a1.75 1.75 0 0 1 3.5 0");
}

</style>

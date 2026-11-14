<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1y3t544w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shopping-trip" /></template>
<style>
.b1y3t544w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 8.5h9l1 9.5h-11Zm2 0C13.5 4 16 4 16 8.5m0 0c0-4.5 2.5-4.5 2.5 0m-16 13h.01M5 20h.01m2.49-1.25h.01M4.5 16.5h.01");
}

</style>

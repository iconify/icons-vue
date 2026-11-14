<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgmmg8g7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shrink-risk" /></template>
<style>
.hgmmg8g7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 11.673V9.25l2.25 1L21 6l-5.5-3C15 4.75 13.75 5.75 12 5.75S9 4.75 8.5 3L3 6l1.75 4.25l2.25-1V21h6.527M18 14.5v7m-3-3l3 3l3-3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfiwt5b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:media-list" /></template>
<style>
.vfiwt5b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 4h9.25A4.375 4.375 0 0 1 21 8.375v7.25A4.375 4.375 0 0 1 16.625 20h-9.25A4.375 4.375 0 0 1 3 15.625v-7.25A4.375 4.375 0 0 1 7.375 4M7 8h.01M7 12h.01M7 16h.01M10 8h7m-7 4h7m-7 4h4.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-0ovhbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:receipt-printer" /></template>
<style>
.m-0ovhbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.5h18v9H3Zm4.5 0V5L9 3.5L10.5 5L12 3.5L13.5 5L15 3.5L16.5 5v6.5M10 8.25h4M17 16h.01");
}

</style>

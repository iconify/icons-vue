<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5cl9bc8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-walk" /></template>
<style>
.m5cl9bc8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM13 9.25L11 15m-3.5 6.5L11 15l3 3l1 3.5m-6.5-8l1.5-3.25l2.75-.5L16.5 13");
}

</style>

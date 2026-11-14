<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-mxv8aso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-birthday" /></template>
<style>
.c-mxv8aso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16h18v5.5H3Zm3-4.5h12V16H6Zm6-2.75v2.75m0-9c1 1 1.5 1.5 1.5 2a1.5 1.5 0 0 1-3 0c0-.5.5-1 1.5-2Z");
}

</style>

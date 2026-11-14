<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz_qe-1hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-based-aisle" /></template>
<style>
.mz_qe-1hc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.634 21H3.5V9L6 5V2.5h5.5V5L14 9v4.166M3.5 9H14m-.5 12c0-5 3-7 8-7c0 5-3 7-8 7Zm0 0l4.5-4.25");
}

</style>

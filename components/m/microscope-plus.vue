<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4ow_nblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microscope-plus" /></template>
<style>
.w4ow_nblt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h4V11h-4Zm4 2.5c5 0 6.5 6 3 10v.171M3.5 14h6m-6 4.5h8.7M18 15v6m-3-3h6");
}

</style>

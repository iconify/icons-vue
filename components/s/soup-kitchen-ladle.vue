<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wshfrcclw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soup-kitchen-ladle" /></template>
<style>
.wshfrcclw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19M20 10v7a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 17v-7m9.5 0L19 3.5M8 7C7 6 9 4.5 8 3m3.25 4c-1-1 1-2.5 0-4");
}

</style>

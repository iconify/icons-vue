<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqna2gbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nutrient-npk" /></template>
<style>
.iqna2gbhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5h8c2.5 2.5 3.5 6 3.5 10c0 2.25-1.5 3.5-3.5 3.5H8c-2 0-3.5-1.25-3.5-3.5c0-4 1-7.5 3.5-10Zm0 0L6.5 3h11L16 7.5m-7 6v3m3-3v3m3-3v3");
}

</style>

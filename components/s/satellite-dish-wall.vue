<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu1ha4bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-dish-wall" /></template>
<style>
.xu1ha4bqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5a6.75 6.75 0 0 0 9.5 9.5ZM6 13l-3 4.5m7.75-9.25L15 4M3 14.5V21m12.5-3.5l3-2.75l3 2.75v4h-6Z");
}

</style>

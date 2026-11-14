<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evgljebub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spinnaker" /></template>
<style>
.evgljebub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18h18l-2.5 3h-13Zm5 0V3m0 .5c8-1 14.5 4.5 12 9.5c-1 1.25-3 2-5.5 2C13 11 11 6.5 8 3.5Zm0 5L4.5 15H8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltx94cbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measure-speed" /></template>
<style>
.ltx94cbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 17a8.5 8.5 0 1 1 14.5-6M11 11l4.5-4.5m0 9.5l2.75 2.75l-2.75 2.75m3.25-5.5l2.75 2.75l-2.75 2.75");
}

</style>

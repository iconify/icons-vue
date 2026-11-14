<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw69u-bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:non-compete" /></template>
<style>
.bw69u-bri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 3h4.5v18.5H16Zm0 6l4.5-4M16 14.5l4.5-4M16 20l4.5-4M7 4.5H3.5v15H7M5.5 12h7M10 9.5l2.5 2.5l-2.5 2.5");
}

</style>

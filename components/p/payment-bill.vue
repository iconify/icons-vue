<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c97l-qbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payment-bill" /></template>
<style>
.c97l-qbbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.778 19.667L10.5 19.5L8 21l-2.25-1.5L3.5 21V2.5h14v9.1m-4.16 9.174L13 21l-.336-.202M7 7h7m-7 4h7m-7 4h3.5m9-1.5L15.75 18h4l-3 4");
}

</style>

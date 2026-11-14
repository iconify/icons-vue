<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_vwujb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-growth-arrow" /></template>
<style>
.j_vwujb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5V13m0 0c0-3-2-5-5.5-5c0 3 2 5 5.5 5Zm0 0c0-3.5 1.5-6 4-6c0 3-1.5 5.25-4 6Zm9.5 7.5V4M16 6.5L18.5 4L21 6.5");
}

</style>

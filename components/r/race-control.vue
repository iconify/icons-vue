<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2hg_1cxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-control" /></template>
<style>
.b2hg_1cxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.928 3h12.144a1.75 1.75 0 0 1 1.66 2.303l-.833 2.5A1.75 1.75 0 0 1 17.239 9H6.761a1.75 1.75 0 0 1-1.66-1.197l-.833-2.5A1.75 1.75 0 0 1 5.928 3M10 3v18m4-18v18m-7 0h10");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yax2zg5gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-screen" /></template>
<style>
.yax2zg5gj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 3.5c-.8 0-1.3.5-1.5 1.25l-.75 3c-.15.75.15 1.35.75 1.75l1.5 1c-1.2 2.5-2.4 3.8-5 5l-1-1.5c-.4-.6-1-.9-1.75-.75l-3 .75c-.75.2-1.25.7-1.25 1.5v3c0 1.1.9 2 2 2c8 0 15-7 15-15c0-1.1-.9-2-2-2Zm-10 6a4 4 0 0 1 4-4m-7 4a7 7 0 0 1 7-7");
}

</style>

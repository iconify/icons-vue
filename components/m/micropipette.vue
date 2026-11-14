<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7qqi3-sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:micropipette" /></template>
<style>
.y7qqi3-sw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.475 4.197l2.828 2.828l-7.778 7.778l-2.828-2.828ZM10 13.5l-2 2m10-10l1.75-1.75M18.5 2.5L21 5M5.5 17.5c1.25 1.25 1.75 2 1.75 2.5a1.75 1.75 0 0 1-3.5 0c0-.5.5-1.25 1.75-2.5Z");
}

</style>

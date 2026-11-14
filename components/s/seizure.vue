<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6kbq4bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seizure" /></template>
<style>
.e6kbq4bjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2.25 5h2.25c1.5 0 2.5.5 3 1.75l2 3c.5 1-.25 1.75-1.25 1.75c-.75 0-1.25-.5-1.5-1L15.25 13l.5 2.25l.75 5c.25.75-.25 1.25-1 1.25h-1.25c-.5 0-1-.4-1-1l-.5-4a.781.781 0 0 0-1.5 0l-.5 4c0 .6-.5 1-1 1H8.5c-.75 0-1.25-.5-1-1.25l.75-5l.5-2.25l-1.25 1.75c-.25.5-.75 1-1.5 1c-1 0-1.75-.75-1.25-1.75l2-3c.5-1.25 1.5-1.75 3-1.75ZM3.5 4l.75 1.25L3.5 6.5l.75 1.25M20.5 4l-.75 1.25l.75 1.25l-.75 1.25M6 2.5l.75 1.25L6 5l.75 1.25M18 2.5l-.75 1.25L18 5l-.75 1.25");
}

</style>

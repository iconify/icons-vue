<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnh8ggp1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shepherd" /></template>
<style>
.pnh8ggp1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5c0-3.25 3.25-5.5 7.5-5.5s7.5 2.25 7.5 5.5c0 .6-.4 1-1 1H4c-.6 0-1-.4-1-1ZM6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm14 14.5V5A1.75 1.75 0 0 0 17 5v1");
}

</style>

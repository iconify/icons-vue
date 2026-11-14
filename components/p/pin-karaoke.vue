<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="unfms0bro"/><path class="ycjeosb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-karaoke" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unfms0bro {
  d: path("M10 2.5h4A1.5 1.5 0 0 1 15.5 4v8a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 12V4A1.5 1.5 0 0 1 10 2.5Z");
}

.ycjeosb2d {
  d: path("M5 11a7 7 0 0 0 14 0m-7 7v3.5m-3.5 0h7");
}

</style>

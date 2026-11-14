<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgcktzb1y"/><path class="u4a6hrbqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speech-to-text" /></template>
<style>
.fgcktzb1y {
  d: path("M3.5 4h5v9h-5Z");
}

.u4a6hrbqj {
  d: path("M2 11a4 4 0 0 0 8 0m-4 4v4m7-11h8m-8 4h8m-8 4h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

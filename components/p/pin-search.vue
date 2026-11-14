<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="szgbmkb4d"/><path class="w7er6-bbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-search" /></template>
<style>
.szgbmkb4d {
  d: path("M9 19S3.5 14 3.5 8.5a5.5 5.5 0 0 1 11 0C14.5 14 9 19 9 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7er6-bbl {
  d: path("M7 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8 8.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM19 19l1.75 1.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="by-xlly8g"/><path class="e0zskrsyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tenant" /></template>
<style>
.by-xlly8g {
  d: path("M3.5 21.5V4A1.5 1.5 0 0 1 5 2.5h9A1.5 1.5 0 0 1 15.5 4v17.5m0-19l5 2v15l-5 2Zm-13 19h19");
}

.e0zskrsyy {
  d: path("M7 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-.75 13c0-3.75 1.5-6.25 3.25-6.25s3.25 2.5 3.25 6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

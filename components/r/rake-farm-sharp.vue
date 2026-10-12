<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6bc1czqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rake-farm-sharp" /></template>
<style>
.u6bc1czqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 2.75L10 14m-4-4l8 8m-7-7l-2.5 2.5m5.5.5l-2.5 2.5m5.5.5l-2.5 2.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmp8x-b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pipe-leak-sharp" /></template>
<style>
.bmp8x-b8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h6.5v4.5h-6.5zm12 0h6.5v4.5h-6.5zm-5.5-1.5h5.5v7.5h-5.5zM12 14.25c-1.25 1.5-2.25 2.75-2.25 4a2.25 2.25 0 0 0 4.5 0c0-1.25-1-2.5-2.25-4Z");
}

</style>

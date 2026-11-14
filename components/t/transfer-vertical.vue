<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k92s45bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transfer-vertical" /></template>
<style>
.k92s45bba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 4v11m3.5-3.5L17 20l-3.5-3.5M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-4V4m3.5 3.5L7 4L3.5 7.5");
}

</style>

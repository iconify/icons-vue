<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zns9f7bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rubber-material" /></template>
<style>
.zns9f7bcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9c2.5 1.25 5.5 1.25 8 0a3 3 0 0 1 0 6a9 9 0 0 0-8 0a3 3 0 0 1 0-6ZM6.25 4.25h11.5M8 2.5L6.25 4.25L8 6m8-3.5l1.75 1.75L16 6M6.25 19.75h11.5M8 18l-1.75 1.75L8 21.5m8-3.5l1.75 1.75L16 21.5");
}

</style>

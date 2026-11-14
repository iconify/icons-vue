<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx3o5bxxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:uv-index-beach" /></template>
<style>
.kx3o5bxxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 19.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-9-17v1m0 11v1M5.5 9h1m11 0h1M7.25 4.25L8 5m8.75-.75L16 5m-8.75 8.75L8 13m8.75.75L16 13");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axlp28hye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:martial-arts" /></template>
<style>
.axlp28hye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5h5v7h-5Zm0 1.25c-3 0-5-.25-7-1.25m0 3.75c2 1 4 1 7 1m5-3.5c3 0 5-.25 7-1.25m0 3.75c-2 1-4 1-7 1m-4 2.25l-3 8h3.25l1-8m.5 0l1 8h3.25l-3-8");
}

</style>

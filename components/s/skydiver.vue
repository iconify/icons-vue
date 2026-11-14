<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxro-6euu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skydiver" /></template>
<style>
.wxro-6euu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10c0-5.5 4-7.5 9-7.5s9 2 9 7.5q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0Q5.25 8.5 3 10Zm0 0l6.75 6.5L7.5 10M21 10l-6.75 6.5L16.5 10m-6.75 6.5h4.5v5h-4.5Z");
}

</style>

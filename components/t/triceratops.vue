<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi-zpnfjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:triceratops" /></template>
<style>
.zi-zpnfjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 19.5c-5.5-2-7-11-2.5-16c2 2 3.5 4 4.5 5.5l6 1.5l2-4l.25 4.5l2.25 2.5L19 16h-6.5Zm3.5-10l3.75-6.25M14 13h.01");
}

</style>

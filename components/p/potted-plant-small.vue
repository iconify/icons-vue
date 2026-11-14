<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sir87dgiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potted-plant-small" /></template>
<style>
.sir87dgiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.5h11l-1.5 8H8Zm5.5 0V9m0 1c-3.5 0-6-2-6-5.5c3.5 0 6 2 6 5.5Zm0-1c3.5 0 6-2 6-5.5c-3.5 0-6 2-6 5.5Z");
}

</style>

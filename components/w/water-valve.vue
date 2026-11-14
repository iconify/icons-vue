<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvjjs1bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-valve" /></template>
<style>
.lvjjs1bfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h5v5h-5Zm14 0h5v5h-5Zm-9 2.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM12 10V5M8 5h8");
}

</style>

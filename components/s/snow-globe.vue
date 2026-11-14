<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siv9ynb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-globe" /></template>
<style>
.siv9ynb2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0ZM7 19h10l1 2H6ZM9 8h.01m3.49 4h.01M15 8h.01");
}

</style>

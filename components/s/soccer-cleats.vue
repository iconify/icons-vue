<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcejkl1cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-cleats" /></template>
<style>
.bcejkl1cz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 3.5l6.5 1l.5 5.5c5.5.5 11 2 11 6v1.5h-18Zm2.5 14v3m5.5-3v3m6.5-3v3");
}

</style>

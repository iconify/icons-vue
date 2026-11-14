<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2id-e4gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ocean-thermal" /></template>
<style>
.k2id-e4gg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 15V4.5a1.5 1.5 0 0 1 3 0V15a3 3 0 1 1-3 0Zm-8-3q1-2 2 0t2 0m11 0q1-2 2 0t2 0m-19 5q1-2 2 0t2 0m11 0q1-2 2 0t2 0");
}

</style>

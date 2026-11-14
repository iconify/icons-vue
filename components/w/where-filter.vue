<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfk32x1fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:where-filter" /></template>
<style>
.gfk32x1fl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12h12.5m-19 0l2 2l3-4M9 5h2m2.75 0h2m2.75 0h3M9 19h2m2.75 0h2m2.75 0h3");
}

</style>

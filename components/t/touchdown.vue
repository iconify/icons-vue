<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj3mqvbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:touchdown" /></template>
<style>
.gj3mqvbte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 2.5v6h8v-6m-4 6v4M3 21a7.75 7.75 0 0 1 9.5-9.5A7.75 7.75 0 0 1 3 21Zm2.5-2.5L10 14m-4.25 2.75l1.5 1.5m1-4l1.5 1.5");
}

</style>

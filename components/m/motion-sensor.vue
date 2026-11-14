<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1gfz2ufw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:motion-sensor" /></template>
<style>
.h1gfz2ufw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5v17m0-13a4.5 4.5 0 0 1 0 9m6.495-8.25a7.5 7.5 0 0 1 0 7.5m3.031-9.25a11 11 0 0 1 0 11m3.031-12.75a14.5 14.5 0 0 1 0 14.5");
}

</style>

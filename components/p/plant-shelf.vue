<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4cp00b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-shelf" /></template>
<style>
.o4cp00b9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5h19M4 16.5v4l3.5-4m12.5 0v4l-3.5-4m-9-6h9l-1.25 6h-6.5Zm4.5 0V7.75c-.25-3-2.25-5-5.25-5c0 3 2.25 5 5.25 5c.25-3.25 2.25-5.25 5.25-5.25c0 3-2 5.25-5.25 5.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_uy-059y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spiral" /></template>
<style>
.o_uy-059y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12a1.75 1.75 0 0 1 3.5 0a3.5 3.5 0 0 1-7 0a5.25 5.25 0 0 1 10.5 0a7 7 0 0 1-14 0a8.75 8.75 0 0 1 17.5 0");
}

</style>

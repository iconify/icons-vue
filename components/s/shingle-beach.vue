<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1vmilb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shingle-beach" /></template>
<style>
.o1vmilb0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5a3.75 3 0 1 0 7.5 0a3.75 3 0 1 0-7.5 0Zm10.5.25a4.25 3 0 1 0 8.5 0a4.25 3 0 1 0-8.5 0ZM8.5 11a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0ZM3 5q2.25-1.25 4.5 0T12 5t4.5 0T21 5");
}

</style>

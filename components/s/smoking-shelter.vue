<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6wn7pq7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smoking-shelter" /></template>
<style>
.l6wn7pq7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8L12 3.25L21.5 8m-17-1v14.5M19.5 7v14.5m-12.25-4h9.5v3h-9.5Zm3.25 0v3m5-6c-1.25-1.5 1.25-3 0-4.5");
}

</style>

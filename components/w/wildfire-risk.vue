<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-9ld1b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wildfire-risk" /></template>
<style>
.n-9ld1b0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 20.5l5.5-7l4 4l4.5-6l5 9ZM12 10c-2 0-3.25-1.25-3.25-2.75c0-1.75 1.75-2.5 2.25-4.5c1 .75 1.5 1.75 1.5 2.75c1-.5 1.5-1.25 1.75-2c1 1 1 2.5 1 3.75C15.25 8.75 14 10 12 10Z");
}

</style>

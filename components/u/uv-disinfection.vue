<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctcvxi4kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:uv-disinfection" /></template>
<style>
.ctcvxi4kh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 8l-4.5 6a5 5 0 1 0 9 0Zm0-5.5v2.75m-7.75 1L6 8m13.75-1.75L18 8M2.5 14h2.25m16.75 0h-2.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyw-wm0bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roots-cutaway" /></template>
<style>
.qyw-wm0bm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h18v11H3Zm9 0V7m0 0Q8 7 7.5 3.5q4 0 4.5 3.5q.5-3.5 4.5-3.5Q16 7 12 7m0 3v8m0-5.5l-4 4m4-4l4 4");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r86448bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roots-cutaway" /></template>
<style>
.r86448bau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 10h12.75A2.625 2.625 0 0 1 21 12.625v5.75A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-5.75A2.625 2.625 0 0 1 5.625 10M12 10V7m0 0Q8 7 7.5 3.5q4 0 4.5 3.5q.5-3.5 4.5-3.5Q16 7 12 7m0 3v8m0-5.5l-4 4m4-4l4 4");
}

</style>

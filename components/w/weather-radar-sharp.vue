<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce7cxrbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:weather-radar-sharp" /></template>
<style>
.ce7cxrbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5a5.66 5.66 0 0 0 8 8Zm4 4l2-2m-2 7.66v4.09m-3 0h6m-.95-15.39a6 6 0 0 1 3.59 3.59m-2.86-6.51a9 9 0 0 1 5.78 5.78");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_1cfkibx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-star" /></template>
<style>
.x_1cfkibx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l2.5 5.75l6 .5l-4.5 4l1.5 6.5L12 16.5l-5.5 3.25l1.5-6.5l-4.5-4l6-.5Z");
}

</style>

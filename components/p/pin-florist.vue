<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t936rydll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-florist" /></template>
<style>
.t936rydll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4v5a5 5 0 0 0 10 0V4l-2.5 2.5L12 4L9.5 6.5Zm5 10v7.5m0-2.5c0-2.5 2.5-4 5.5-4c0 2.5-2.5 4-5.5 4Z");
}

</style>

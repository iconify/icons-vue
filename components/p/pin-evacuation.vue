<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzw7aibnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-evacuation" /></template>
<style>
.qzw7aibnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm.5 4l-2.5 6m-5-4L10 8l4 .5l2.5 3.5M5 18.5l3.5-1l3-3l4 2.5l-.5 4.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1us-3bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microscope-light" /></template>
<style>
.w1us-3bfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h4.5V10H7ZM11.5 5c6 0 8 8.5 4 13v3m-11-2.75h8.25M4.5 21H19M7.75 12.75l-1.5 2.75m4.5-2.75l1.5 2.75");
}

</style>

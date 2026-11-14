<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-9e22mhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traction-control" /></template>
<style>
.z-9e22mhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.5V9.25c0-.5.25-1 1-1.25l1.25-3.5c.25-.75.75-1.25 1.5-1.25h5.5c.75 0 1.25.5 1.5 1.25L17.5 8c.75.25 1 .75 1 1.25v2.25ZM8 21q2.25-1.875 0-3.75t0-3.75m8 7.5q2.25-1.875 0-3.75t0-3.75");
}

</style>

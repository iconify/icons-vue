<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8d-ztzea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quiet-hour" /></template>
<style>
.m8d-ztzea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.85 19.204L6.5 15h-4V9h4l7-5.5v10.098M6.5 9v6m9.75-7.763a5.5 5.5 0 0 1 2.666 3.808M19.5 14.5a3.75 3.75 0 1 0 2.25 5a3 3 0 0 1-2.25-5Z");
}

</style>

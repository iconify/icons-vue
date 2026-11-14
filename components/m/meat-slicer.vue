<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gi-iye4nr"/><path class="x1clfxb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meat-slicer" /></template>
<style>
.gi-iye4nr {
  d: path("M4.5 11a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1clfxb_w {
  d: path("M10 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 21h18M7 18.5V21m10-2.5V21");
}

</style>

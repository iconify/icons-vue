<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w5kzggbel"/><path class="brmfyc00r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:padlock-heavy" /></template>
<style>
.brmfyc00r {
  fill: currentColor;
  d: path("M10.25 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5kzggbel {
  d: path("M2.5 10h19v11.5h-19ZM6 10V8.5a6 6 0 0 1 12 0V10h-2.75V8.5a3.25 3.25 0 0 0-6.5 0V10Z");
}

</style>

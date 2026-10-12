<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m230akszn"/><path class="jhgdx9b0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sharpener-sharp" /></template>
<style>
.jhgdx9b0e {
  d: path("M3.5 10.5h4l.67.34l2.16 1.07l.67.34l-.67.34l-2.16 1.07l-.67.34H2.75v-3.5z");
}

.m230akszn {
  d: path("M8.75 6.25h12.5v12H8.75zm4 3.25h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

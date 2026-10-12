<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tzjml7bul"/><path class="g-0yjsb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speedboat-sharp" /></template>
<style>
.g-0yjsb9n {
  d: path("m9.09 12.26l2.82-4.02l.34-.49h2l-.12.59l-.76 3.82l-.12.59h-4.5zM2.75 20h5m2.75 0h8.25M5 17.25H2.75");
}

.tzjml7bul {
  d: path("M2.75 12.75h12.5l6-2.25l-1.95 5.2l-.485 1.298L17.43 17H7.4l-1.733.001L4.8 15.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

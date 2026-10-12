<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hdvs01bcz"/><path class="ajbywh59w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memory-chip-sharp" /></template>
<style>
.ajbywh59w {
  d: path("M6.25 8.75H8v4H5.5v-4zm10.5 0h1.75v4H16v-4zm-6.25 0h3v4h-3zm-4.5 7v2.5m3-2.5v2.5m6-2.5v2.5m3-2.5v2.5");
}

.hdvs01bcz {
  d: path("M2.75 5.75h18.5v10H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

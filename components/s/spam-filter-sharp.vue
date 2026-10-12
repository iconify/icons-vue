<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l3r3-tbci"/><path class="k1x55051s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spam-filter-sharp" /></template>
<style>
.k1x55051s {
  d: path("m3.5 5l6 4.25l6-4.25m-3 11.25h8.75l-.57.48l-2.11 1.79L18 19v2.25h-3V19l-.57-.48l-2.11-1.79l-.57-.48z");
}

.l3r3-tbci {
  d: path("M2.75 3.75h13.5v10H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

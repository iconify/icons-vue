<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k012gh4pj"/><path class="d1knrmpub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peeler-sharp" /></template>
<style>
.d1knrmpub {
  d: path("M7.75 2.75h8.5v5h-8.5zM10 5.25h4M10.25 15h3.5v6.25h-3.5z");
}

.k012gh4pj {
  d: path("M4.75 2.75v5L12 15l7.25-7.25v-5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g9gs7-49h"/><path class="ddkmklbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smartwatch-sharp" /></template>
<style>
.ddkmklbqa {
  d: path("M8 12h1.75L11 9.75l1.75 4.5L14 12h1.75");
}

.g9gs7-49h {
  d: path("M5.75 5.75h11.5v12.5H5.75zm2.75 0v-3h6v3m-6 12.5v3h6v-3m5.25-7.75v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dbj3d8fha"/><path class="lix-bvb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zodiac-virgo-sharp" /></template>
<style>
.dbj3d8fha {
  d: path("M3.75 6.5H6v13.75M6 9V6.5h5v13.75M11 9V6.5h5v13.75");
}

.lix-bvb9h {
  d: path("M16 13c2.75-1 4.25.5 4.25 2.5c0 2.5-2.25 4.25-6 4.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

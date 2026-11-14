<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sg8pxe_xu"/><path class="d6er6k2fz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-nightclub" /></template>
<style>
.d6er6k2fz {
  d: path("M7 14.5a3 6.5 0 1 0 6 0a3 6.5 0 1 0-6 0Zm11-12Q18 5 20.5 5Q18 5 18 7.5Q18 5 15.5 5Q18 5 18 2.5Z");
}

.sg8pxe_xu {
  d: path("M10 2.5V8m-6.5 6.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm0 0h13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

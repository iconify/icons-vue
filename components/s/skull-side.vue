<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r06i-wtfd"/><path class="e1-dzydke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skull-side" /></template>
<style>
.e1-dzydke {
  d: path("M8 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7 18h5.5l2-2.5");
}

.r06i-wtfd {
  d: path("M5 11.5c0-5.5 3.5-9 8.5-9s8 3.5 8 8c0 3.5-2 5.5-4.5 6l-1 4c0 .5-.5 1-1 1H8.5L7 18H5l-1.5-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

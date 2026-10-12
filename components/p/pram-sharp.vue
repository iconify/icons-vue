<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h00-h3tfz"/><circle class="yc4v2ie2d"/><circle class="za7uslb4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pram-sharp" /></template>
<style>
.h00-h3tfz {
  d: path("M3.75 10a7 7 0 0 1 7-7v7Zm0 0h16.5c0 3.25-2.75 5.5-6.25 5.5h-4c-3.5 0-6.25-2.25-6.25-5.5Zm14.75 0l1.25-5.5h1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc4v2ie2d {
  cx: 7.75px;
  cy: 19.5px;
  r: 1.75px;
}

.za7uslb4r {
  cx: 16.25px;
  cy: 19.5px;
  r: 1.75px;
}

</style>

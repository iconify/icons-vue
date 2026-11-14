<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i_jo6mb3j"/><path class="wn2y5rbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-steering-warning" /></template>
<style>
.i_jo6mb3j {
  d: path("M2.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn2y5rbcn {
  d: path("M8 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-5.5 0H8m4 0h5.5M10 14v5.5M20.75 7v6.5m0 3.5h.01");
}

</style>

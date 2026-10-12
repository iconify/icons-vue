<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh2g22btx"/><path class="ha8apkuln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:priority-sharp" /></template>
<style>
.bh2g22btx {
  d: path("M5.25 9.5L12 2.75l6.75 6.75");
}

.ha8apkuln {
  d: path("M5.25 14.75L12 8l6.75 6.75M5.25 20L12 13.25L18.75 20");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

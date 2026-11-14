<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w5w-4exyg"/><path class="d5lrbtbzb"/><path class="czz54ekku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wheelchair-tennis" /></template>
<style>
.czz54ekku {
  d: path("M16 3.5q1.75 2 0 4m5.5-4q-1.75 2 0 4");
}

.d5lrbtbzb {
  d: path("M13.005 12.345a5.5 5.5 0 1 1-9.01 0M15.5 5.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5w-4exyg {
  d: path("M6.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 3.5v4.5H14l2.5 7");
}

</style>

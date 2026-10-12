<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ixi6_5bec"/><path class="q8x8imr2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spell-book-sharp" /></template>
<style>
.ixi6_5bec {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.25 0v18.5");
}

.q8x8imr2y {
  d: path("M13.75 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

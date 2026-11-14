<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9e36qb2f"/><path class="y5q52dczf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-jersey" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9e36qb2f {
  d: path("M3.5 3h17v18h-17Z");
}

.y5q52dczf {
  d: path("M9 3a3 3 0 0 0 6 0M8 9v12m8-12v12");
}

</style>

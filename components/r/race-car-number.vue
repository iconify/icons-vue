<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v538tj8qb"/><path class="m4h4_xbgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-car-number" /></template>
<style>
.m4h4_xbgd {
  d: path("M4.5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-5.75-7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v538tj8qb {
  d: path("M2.5 15.5V12q0-1.5 1.5-1.75l3-.5l3-4.25h5l3.5 4.25l1.5.5q1.5.25 1.5 1.75v3.5Z");
}

</style>

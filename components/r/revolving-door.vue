<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw9-e9bgk"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:revolving-door" /></template>
<style>
.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw9-e9bgk {
  d: path("M13.5 21.5h-9v-19h12v7.3m-9-.8l3-3m-3 6.5l6-6m0 4.5v1.8m6 2.352A3 3 0 0 1 18 20.75m-1.5-.402A3 3 0 0 1 18 14.75");
}

</style>

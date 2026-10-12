<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ynf6gdd5u"/><path class="mjy5fbbwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wire-sharp" /></template>
<style>
.mjy5fbbwl {
  d: path("M10.25 9.75h5.5v4.5h-5.5zm7.25.75l3.75-1.75M17.5 12h3.75m-3.75 1.5l3.75 1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ynf6gdd5u {
  d: path("M2.75 18.25C7.25 18.25 6 12 10.5 12");
}

</style>

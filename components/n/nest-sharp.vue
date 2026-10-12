<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a4rhc5brf"/><path class="n0h--eokr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nest-sharp" /></template>
<style>
.a4rhc5brf {
  d: path("M2.75 12.25h18.5c0 4.75-4 9-9.25 9s-9.25-4.25-9.25-9Z");
}

.n0h--eokr {
  d: path("M5.25 15.25L12 17.5l6.75-2.25M7.75 19l8.5-2.75m-10.75-4V10a2.5 3 0 0 1 5 0v2.25Zm7.25 0V9a2.75 3.25 0 0 1 5.5 0v3.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

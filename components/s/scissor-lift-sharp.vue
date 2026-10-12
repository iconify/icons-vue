<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="aaje8gbah"/><circle class="xebcnrxsr"/><circle class="sxv9vqbas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scissor-lift-sharp" /></template>
<style>
.aaje8gbah {
  d: path("M2.75 7h18.5M5 7V2.75h14V7M5.5 10l13 5.25m0-5.25l-13 5.25m-2.75 3h18.5");
}

.sxv9vqbas {
  cx: 18px;
  cy: 19.75px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xebcnrxsr {
  cx: 6px;
  cy: 19.75px;
  r: 1.5px;
}

</style>

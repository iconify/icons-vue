<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nouken32h"/><path class="kr7popbxw"/><path class="gordk1bna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rotate-clockwise-linear" /></template>
<style>
.gordk1bna {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 6.986L22 8C22 4.985 19.8377 2.483 17 2");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr7popbxw {
  stroke-linecap: round;
  d: path("M17.5 10.0071C19.3597 10.0331 20.414 10.1711 21.1213 10.8791C22 11.7571 22 13.1721 22 16.0001C22 18.8281 22 20.2431 21.1213 21.1211C20.414 21.8291 19.3597 21.9671 17.5 21.9941");
}

.nouken32h {
  d: path("M8 22H9C11.8284 22 13.2426 22 14.1213 21.121C15 20.243 15 18.829 15 16V8C15 5.172 15 3.757 14.1213 2.879C13.2426 2 11.8284 2 9 2H8C5.1716 2 3.7574 2 2.8787 2.879C2 3.757 2 5.172 2 8V16C2 18.829 2 20.243 2.8787 21.121C3.7574 22 5.1716 22 8 22Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vq0g1_bdd"/><path class="gvv-5m57t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scarf-sharp" /></template>
<style>
.gvv-5m57t {
  d: path("M13.5 8.25h3l-.33.67l-4.09 8.41l-.33.67h-6.5l.46-.59l6.58-8.57l.46-.59zM6 18v3.25M8.5 18v3.25M11 18v3.25");
}

.vq0g1_bdd {
  d: path("M9.25 9.75c-2.75-2.75-1.5-7 2.75-7s4.75 3.25 3.5 5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

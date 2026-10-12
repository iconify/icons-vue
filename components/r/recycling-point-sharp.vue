<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="ovi-hdc4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recycling-point-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.ovi-hdc4u {
  d: path("m13.08 7.93l3.24 5.81m-2.09-.67l2.09.67l.53-2.13m-1.01 5.14H9.36m1.6-1.5l-1.6 1.5l1.6 1.5m-3.88-3.44l3.24-5.8m.53 2.13l-.53-2.13l-2.09.67");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

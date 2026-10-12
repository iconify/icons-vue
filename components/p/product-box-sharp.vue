<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oug80qbep"/><path class="iy4fw-hac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:product-box-sharp" /></template>
<style>
.iy4fw-hac {
  d: path("M8 14h8v4.5H8zm2.5 2.25h3");
}

.oug80qbep {
  d: path("M2.75 3.75h18.5v4.5H2.75zm1 7.5h16.5v10H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

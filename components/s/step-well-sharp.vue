<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="to5pz9bns"/><path class="wp1hd9bsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:step-well-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.to5pz9bns {
  d: path("M5.75 6.75v-1h12.5v12.5H5.75v-1ZM8.25 9v-.75h7.5v7.5h-7.5V15Z");
}

.wp1hd9bsq {
  d: path("M10.75 10.75h2.5v2.5h-2.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

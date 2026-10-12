<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z_ww9gnmb"/><path class="j4tlezknq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transistor-sharp" /></template>
<style>
.j4tlezknq {
  d: path("M2.75 12h7m0-2l5-3.25v-4M9.75 14l5 3.25v4m-2.81-4.34l2.56.18l-1.2-2.28M9.75 7.5v9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_ww9gnmb {
  d: path("M21.25 12a8.25 8.25 0 1 1-16.5 0a8.25 8.25 0 1 1 16.5 0");
}

</style>

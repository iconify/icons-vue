<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="x5w4u_bzm"/><path class="embitybap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wind-direction-sharp" /></template>
<style>
.embitybap {
  d: path("M6.16 16.34L17.5 5m0 0l3.54 1.41m-6.01 1.06l3.54 1.41");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5w4u_bzm {
  cx: 4.75px;
  cy: 17.75px;
  r: 2px;
}

</style>

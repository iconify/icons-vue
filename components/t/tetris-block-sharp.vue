<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sblgsowld"/><path class="bqq80sb8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tetris-block-sharp" /></template>
<style>
.bqq80sb8v {
  d: path("M4.25 3H21v12h-6V9H3V3zM9 3v6m6-6v6m0 0h6");
}

.sblgsowld {
  d: path("M10.25 9H15v6h6v6H3v-6h6V9zM9 15v6m6-6v6m-6-6h6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0n8-nvma"/><path class="pu-22dblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-delivery" /></template>
<style>
.g0n8-nvma {
  d: path("M2.5 16.5V7A1.5 1.5 0 0 1 4 5.5h11l6.5 5.5v5.5Z");
}

.pu-22dblz {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0-13V11h6.5M8.75 13.75v-2.5c-.25-1.75-1.5-3-3.5-3c0 1.75 1.5 3 3.5 3c.25-2 1.5-3 3.5-3c0 1.75-1.5 3-3.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

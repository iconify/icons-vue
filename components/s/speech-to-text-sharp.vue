<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vsudofb_g"/><path class="rhlfdw6xa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speech-to-text-sharp" /></template>
<style>
.rhlfdw6xa {
  d: path("M2.75 10.75a5.25 5.25 0 0 0 10.5 0M8 16v4.5M15.75 8h5.5m-5.5 4.25h5.5m-5.5 4.25h3.5");
}

.vsudofb_g {
  d: path("M5 2.75h6v10.5H5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

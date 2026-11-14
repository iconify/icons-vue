<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u88i1b-wn"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tee-time" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.u88i1b-wn {
  d: path("M4 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM6 15l3 2.5l3-2.5m-3 2.5v4m5.75-3.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

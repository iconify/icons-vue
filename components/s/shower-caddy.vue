<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="va-f73bkm"/><path class="eldei4bgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shower-caddy" /></template>
<style>
.eldei4bgr {
  d: path("M8.5 8.5h3V10l1.5 1.5v6.75H7V11.5L8.5 10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.va-f73bkm {
  d: path("M2.5 5h19m-18 7v6.75A2.25 2.25 0 0 0 5.75 21h11A2.25 2.25 0 0 0 19 18.75V5a2 2 0 0 0-4 0v1.5");
}

</style>

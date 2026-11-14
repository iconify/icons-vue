<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufipflbct"/><path class="qqzb4qbmy"/><path class="lo-aaohyg"/><path class="y1j4t4bgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stone-cairn" /></template>
<style>
.lo-aaohyg {
  d: path("M7.25 8a4.75 2.25 0 1 0 9.5 0a4.75 2.25 0 1 0-9.5 0Z");
}

.qqzb4qbmy {
  d: path("M5.5 12.75a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0Z");
}

.ufipflbct {
  d: path("M3.5 18a8.5 2.75 0 1 0 17 0a8.5 2.75 0 1 0-17 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1j4t4bgr {
  d: path("M9 4a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0Z");
}

</style>

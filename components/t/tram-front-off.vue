<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kql3c-ebw"/><path class="i88y1sd6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-off" /></template>
<style>
.i88y1sd6n {
  fill: currentColor;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16Z");
  stroke: none;
}

.kql3c-ebw {
  d: path("M19.1213 19.1213C18.5785 19.6642 17.8285 20 17 20L7 20C5.3431 20 4 18.6569 4 17L4 9C4 7.6462 4.8967 6.5019 6.1285 6.1285M4 12L12 12M8 20L7 22M16 20L17 22M11.6569 6L17 6C18.6569 6 20 7.3431 20 9L20 14.3431M17.6569 12L20 12M8 2L16 2M10.5523 4.8954L12 2L14 6M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

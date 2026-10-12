<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f48mmqbbf"/><path class="pzntaqbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spectrometer-sharp" /></template>
<style>
.f48mmqbbf {
  d: path("M5.5 7h8.75v10H5.5z");
}

.pzntaqbfy {
  d: path("m9.88 9.5l2.75 4.75h-5.5ZM2.75 12H5.5m2.25 5v4.25M12 17v4.25M14.25 12l7-4.5m-7 4.5h7m-7 0l7 4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

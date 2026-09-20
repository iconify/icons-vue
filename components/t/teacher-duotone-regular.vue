<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q0vdzdb3o"/><path class="x47uatb1d"/><path class="w9kno3b1a"/><path class="vfo57uyzf"/><path class="d19ei8m3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:teacher-duotone-regular" /></template>
<style>
.d19ei8m3q {
  d: path("M2 18a4 4 0 0 1 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q0vdzdb3o {
  fill: currentColor;
  d: path("M10 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vfo57uyzf {
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w9kno3b1a {
  d: path("M10 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
}

.x47uatb1d {
  fill: currentColor;
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

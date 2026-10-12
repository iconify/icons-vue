<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wvfgahait"/><path class="w-3bdibcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zodiac-wheel-sharp" /></template>
<style>
.w-3bdibcb {
  d: path("m12 9l.36 2.64L15 12l-2.64.36L12 15l-.36-2.64L9 12l2.64-.36z");
}

.wvfgahait {
  d: path("M2.75 12a9.25 9.25 0 1 0 18.5 0a9.25 9.25 0 1 0-18.5 0M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0m11.8 1.55l3.13.84m-4.69 1.85l2.3 2.3m-4.99-.74l.84 3.13m-3.94-3.13l-.84 3.13m-1.85-4.69l-2.3 2.3m.74-4.99l-3.13.84m3.13-3.94l-3.13-.84m4.69-1.85l-2.3-2.3m4.99.74l-.84-3.13m3.94 3.13l.84-3.13m1.85 4.69l2.3-2.3m-.74 4.99l3.13-.84");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

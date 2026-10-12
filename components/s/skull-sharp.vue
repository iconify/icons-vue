<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fsura4b_z"/><path class="jcy1bvbzr"/><path class="w763aicii"/><path class="rm3k2mxiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skull-sharp" /></template>
<style>
.fsura4b_z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.75 14l4.51 1.55M19.25 19l-4.51-1.55M4.75 19l4.51-1.55M19.25 14l-4.51 1.55");
}

.jcy1bvbzr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.22 14.77h.01m.58-1.7h.01m14.96 5.16h.01m-.6 1.7h.01m-14.39 0h.01m-.6-1.7h.01m14.96-5.16h.01m.58 1.7h.01");
}

.rm3k2mxiv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8a.75.75 0 1 0 1.5 0A.75.75 0 1 0 9 8m4.5 0A.75.75 0 1 0 15 8a.75.75 0 1 0-1.5 0");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w763aicii {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12.04a6.25 4.5 0 1 1 5.5 0V18h-5.5v-1Z");
}

</style>

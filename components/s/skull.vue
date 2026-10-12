<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fsura4b_z"/><path class="jcy1bvbzr"/><path class="r6050x3ek"/><path class="rm3k2mxiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skull" /></template>
<style>
.fsura4b_z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.75 14l4.51 1.55M19.25 19l-4.51-1.55M4.75 19l4.51-1.55M19.25 14l-4.51 1.55");
}

.jcy1bvbzr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.22 14.77h.01m.58-1.7h.01m14.96 5.16h.01m-.6 1.7h.01m-14.39 0h.01m-.6-1.7h.01m14.96-5.16h.01m.58 1.7h.01");
}

.r6050x3ek {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12.04a6.25 4.5 0 1 1 5.5 0V17a1 1 0 0 1-1 1h-3.5a1 1 0 0 1-1-1Z");
}

.rm3k2mxiv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8a.75.75 0 1 0 1.5 0A.75.75 0 1 0 9 8m4.5 0A.75.75 0 1 0 15 8a.75.75 0 1 0-1.5 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

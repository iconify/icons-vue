<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l3h0jolru"/><circle class="nl0pxj_sf"/><path class="iz94wgblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:socket-sharp" /></template>
<style>
.iz94wgblf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12h.01m4.49 0h.01");
}

.l3h0jolru {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

.nl0pxj_sf {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

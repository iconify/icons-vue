<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="oeid-s38d"/><path class="wnhst9bwb"/><path class="i7-kopb4y"/><path class="shqarv4xv"/><path class="gn_p0sb7q"/><path class="bo51iypxr"/><path class="zy54a7bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nerf-duotone-bold" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gn_p0sb7q {
  d: path("m3 20 5 -5");
}

.i7-kopb4y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oeid-s38d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 4 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.shqarv4xv {
  d: path("m3 4 5 5");
}

.wnhst9bwb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 20 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>

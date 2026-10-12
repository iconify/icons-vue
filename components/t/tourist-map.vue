<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="c_wohxbvu"/><path class="yd6wn40qn"/><path class="ny2iv2b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tourist-map" /></template>
<style>
.c_wohxbvu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.68 4.89l3.89-1.53Q8.5 3 9.45 3.31l5.1 1.63q.95.31 1.88-.05l3.89-1.53q.93-.36.93.64v13.75q0 1-.93 1.36l-3.89 1.53q-.93.36-1.88.05l-5.1-1.63q-.95-.31-1.88.05l-3.89 1.53q-.93.36-.93-.64V6.25q0-1 .93-1.36");
}

.ny2iv2b7m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 9h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yd6wn40qn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 17c1.5-3 4-2 5.5-4.5s2-3.5 4.25-3.5");
}

</style>

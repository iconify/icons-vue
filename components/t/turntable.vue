<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><circle class="bepmk1bhd"/><path class="h3qkj9bop"/><path class="lnxn6ebus"/><path class="rio5yf-5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turntable" /></template>
<style>
.bepmk1bhd {
  cx: 10px;
  cy: 12px;
  r: 5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.h3qkj9bop {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

.hufrlzpcu {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.lnxn6ebus {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 7v6.5L16 16");
}

.rio5yf-5e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 7h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l7yfq-b6e"/><circle class="bepmk1bhd"/><path class="h3qkj9bop"/><path class="lnxn6ebus"/><path class="rio5yf-5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turntable-sharp" /></template>
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

.l7yfq-b6e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.lnxn6ebus {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 7v6.5L16 16");
}

.rio5yf-5e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 7h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

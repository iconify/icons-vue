<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tm-s59b6a"/><path class="ovotu9bqd"/><path class="jrkx7rb6j"/><path class="rj24c2b0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shark-sharp" /></template>
<style>
.jrkx7rb6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 12.75h.01");
}

.ovotu9bqd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9.75L12.25 5l.539-.943l.261 1.043l.95 4.4");
}

.rj24c2b0o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 12v2.5");
}

.tm-s59b6a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13c2-3 7-4 11.25-3.5l2.6.325l1.9 1.425L21 8.5L20 13l1 4.5l-2.5-2.75c-2 1.25-5 2-8.5 2S4 15.5 2.75 13Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qg1rkpyth"/><path class="wtls0zb1d"/><path class="o93snwb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school-zone-sharp" /></template>
<style>
.o93snwb9s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12.25v3L8.75 18M10 15.25L11.25 18m3-4.5v2.25l-1 2.25m1-2.25l1 2.25M10 13.25l4.25 1");
}

.qg1rkpyth {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.98 4.99l7.29 13.02l.98 1.74H2.75l.98-1.74l7.29-13.02l.98-1.74z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wtls0zb1d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.5h.01m4.24 1.5h.01");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n2wmvdxwf"/><path class="tbsb059st"/><path class="gpvq06blh"/><path class="dg-3pj0zi"/><path class="i857i-b1f"/><path class="mzm25fejl"/><path class="m0hvambgh"/><path class="th7wxwuos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sewing-duotone-regular" /></template>
<style>
.dg-3pj0zi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gpvq06blh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i857i-b1f {
  d: path("M4 20 18 6");
}

.m0hvambgh {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mzm25fejl {
  d: path("m18 6 3 -3");
}

.n2wmvdxwf {
  fill: currentColor;
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tbsb059st {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.th7wxwuos {
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
}

</style>

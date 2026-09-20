<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2wmvdxwf"/><path class="tm7tdosmx"/><path class="ra14n9_co"/><path class="x9f-cgrxf"/><path class="i857i-b1f"/><path class="mzm25fejl"/><path class="m0hvambgh"/><path class="th7wxwuos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sewing-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

.ra14n9_co {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.th7wxwuos {
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
}

.tm7tdosmx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x9f-cgrxf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

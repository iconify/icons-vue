<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4fme0p6q"/><path class="gam3cw54g"/><path class="r9jjpnb6g"/><path class="sv87mbb3y"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="u4c9tcc0l"/><path class="bfj3etm_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pressure-rising-duotone-bold" /></template>
<style>
.bfj3etm_d {
  d: path("M13.5 11H17v3.5");
}

.c4fme0p6q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.r9jjpnb6g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sv87mbb3y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 11H17v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u4c9tcc0l {
  d: path("m12 16 5 -5");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>

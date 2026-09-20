<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu-ymbcar"/><path class="yd1dd2b-v"/><path class="d2j4ppeho"/><path class="sk0dl9znp"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="u4c9tcc0l"/><path class="bfj3etm_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pressure-rising-duotone-thin" /></template>
<style>
.bfj3etm_d {
  d: path("M13.5 11H17v3.5");
}

.d2j4ppeho {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.sk0dl9znp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 11H17v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u4c9tcc0l {
  d: path("m12 16 5 -5");
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

.zu-ymbcar {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emyboub8n"/><path class="tbe304aqf"/><path class="qqcycfb_y"/><path class="k5f1-jb1z"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="u4c9tcc0l"/><path class="bfj3etm_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pressure-rising-duotone-regular" /></template>
<style>
.bfj3etm_d {
  d: path("M13.5 11H17v3.5");
}

.emyboub8n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k5f1-jb1z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 11H17v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qqcycfb_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbe304aqf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u4c9tcc0l {
  d: path("m12 16 5 -5");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>

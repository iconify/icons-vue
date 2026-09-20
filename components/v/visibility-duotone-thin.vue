<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="jw01oqbhb"/><path class="bt_2bvgpa"/><path class="scq6fxlrr"/><path class="ezi2r0-jm"/><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="rkhcgsbdl"/><path class="irm-6r_xs"/><path class="uzi41e83o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:visibility-duotone-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.bt_2bvgpa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ezi2r0-jm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irm-6r_xs {
  d: path("M3 17v4");
}

.jw01oqbhb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.rp243mbkd {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

.scq6fxlrr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uzi41e83o {
  d: path("M21 17v4");
}

</style>

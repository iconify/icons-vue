<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkh2r59sx"/><path class="qrhqs_vfa"/><path class="x8_s66bwx"/><path class="k-jed-9si"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="c4khiwgvb"/><path class="gi1v2vyju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:place-order-duotone-thin" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.gi1v2vyju {
  d: path("M13.5 12.5 16 15l-2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkh2r59sx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k-jed-9si {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 12.5 16 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrhqs_vfa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.x8_s66bwx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

</style>

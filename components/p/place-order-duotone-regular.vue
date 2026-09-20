<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e06o29xir"/><path class="am603abae"/><path class="eljxzwbgp"/><path class="wkjitcbdw"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="c4khiwgvb"/><path class="gi1v2vyju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:place-order-duotone-regular" /></template>
<style>
.am603abae {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c4khiwgvb {
  d: path("M8 15h8");
}

.e06o29xir {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eljxzwbgp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gi1v2vyju {
  d: path("M13.5 12.5 16 15l-2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.wkjitcbdw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 12.5 16 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

</style>

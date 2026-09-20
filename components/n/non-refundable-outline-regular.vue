<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cu26jmb_i"/><path class="x50q_4bdr"/><path class="qaa4bo00g"/><path class="j6apg33fy"/><path class="uy8sxobpv"/><path class="mya0_nbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:non-refundable-outline-regular" /></template>
<style>
.cu26jmb_i {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.j6apg33fy {
  d: path("M16 2.5V5");
}

.mya0_nbso {
  d: path("m8 17.5 6 -6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qaa4bo00g {
  d: path("M8 2.5V5");
}

.uy8sxobpv {
  d: path("M7 12.5h10v6H7Z");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>

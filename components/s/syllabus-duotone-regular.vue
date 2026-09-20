<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyr0_hpav"/><path class="qisq4mbcd"/><path class="yy7evi_9s"/><path class="y4_6s7b5v"/><path class="hg1j_lbce"/><path class="kif3ikiir"/><path class="uv-0dacjj"/><path class="e36i9zwxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:syllabus-duotone-regular" /></template>
<style>
.e36i9zwxh {
  d: path("M11 15h6");
}

.hg1j_lbce {
  d: path("M7 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kif3ikiir {
  d: path("M11 9h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qisq4mbcd {
  fill: currentColor;
  d: path("M7 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uv-0dacjj {
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.yy7evi_9s {
  fill: currentColor;
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zyr0_hpav {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

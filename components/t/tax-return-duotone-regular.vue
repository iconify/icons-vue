<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyr0_hpav"/><path class="mxpiblb0j"/><path class="d41wo7iwm"/><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="gzg_qsbpe"/><path class="fxvoaub7q"/><path class="w82z55b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tax-return-duotone-regular" /></template>
<style>
.d41wo7iwm {
  fill: currentColor;
  d: path("M15.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fxvoaub7q {
  d: path("m11 15 6 -6");
}

.gzg_qsbpe {
  d: path("M10.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mxpiblb0j {
  fill: currentColor;
  d: path("M10.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.w82z55b-g {
  d: path("M15.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wuvisubmw {
  d: path("M8 3v18");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.zyr0_hpav {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

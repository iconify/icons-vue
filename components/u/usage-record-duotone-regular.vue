<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ots31sbwo"/><path class="hhrpd0mfr"/><path class="guoi_acnp"/><path class="jd_dotbnq"/><path class="g587irb4v"/><path class="q3s7g5q_s"/><path class="g-g6w6buq"/><path class="z3-9k3d5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:usage-record-duotone-regular" /></template>
<style>
.g-g6w6buq {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g587irb4v {
  d: path("M7 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.guoi_acnp {
  fill: currentColor;
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hhrpd0mfr {
  fill: currentColor;
  d: path("M7 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ots31sbwo {
  fill: currentColor;
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q3s7g5q_s {
  d: path("M10.5 7H17");
}

.z3-9k3d5e {
  d: path("M10.5 11H17");
}

</style>

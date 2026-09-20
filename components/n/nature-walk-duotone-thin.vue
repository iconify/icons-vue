<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fp8q9j9ui"/><path class="kf1y7kspr"/><path class="a1e-khday"/><path class="liw5fjolu"/><path class="zw_n0_vwa"/><path class="fe670vbuv"/><path class="fmlaifbpn"/><path class="l5q9_cc7w"/><path class="t630gdbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nature-walk-duotone-thin" /></template>
<style>
.a1e-khday {
  fill: currentColor;
  d: path("M2 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fe670vbuv {
  d: path("m12 8 8 8H4Z");
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.fp8q9j9ui {
  fill: currentColor;
  d: path("m12 3 7 7H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kf1y7kspr {
  fill: currentColor;
  d: path("m12 8 8 8H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l5q9_cc7w {
  d: path("M2 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.liw5fjolu {
  fill: currentColor;
  d: path("M7 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t630gdbxd {
  d: path("M7 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zw_n0_vwa {
  d: path("m12 3 7 7H5Z");
}

</style>

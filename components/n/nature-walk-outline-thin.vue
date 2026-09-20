<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zw_n0_vwa"/><path class="fe670vbuv"/><path class="fmlaifbpn"/><path class="l5q9_cc7w"/><path class="t630gdbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nature-walk-outline-thin" /></template>
<style>
.fe670vbuv {
  d: path("m12 8 8 8H4Z");
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5q9_cc7w {
  d: path("M2 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t630gdbxd {
  d: path("M7 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zw_n0_vwa {
  d: path("m12 3 7 7H5Z");
}

</style>

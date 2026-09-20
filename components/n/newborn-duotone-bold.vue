<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qqm3sm-he"/><path class="hs7fock-w"/><path class="ddr0zpdgr"/><path class="f8efap2_b"/><path class="nl66y9men"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:newborn-duotone-bold" /></template>
<style>
.ddr0zpdgr {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.f8efap2_b {
  d: path("M5 21a7 7 0 0 1 14 0Z");
}

.hs7fock-w {
  fill: currentColor;
  d: path("M5 21a7 7 0 0 1 14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nl66y9men {
  d: path("M6 16h12");
}

.qqm3sm-he {
  fill: currentColor;
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

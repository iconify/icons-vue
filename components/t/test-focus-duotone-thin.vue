<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw3g4ocav"/><path class="wil058c_n"/><path class="bybw7n7fq"/><path class="ps2g__eqt"/><path class="d5czi6rdr"/><path class="l-z02yb4d"/><path class="rf0c3ccmk"/><path class="epou1mbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-focus-duotone-thin" /></template>
<style>
.bybw7n7fq {
  fill: currentColor;
  d: path("M9 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.epou1mbuy {
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-z02yb4d {
  d: path("M11 5v5l2.5 -2.5Z");
}

.ps2g__eqt {
  fill: currentColor;
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rf0c3ccmk {
  d: path("M9 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.uw3g4ocav {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wil058c_n {
  fill: currentColor;
  d: path("M11 5v5l2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="kllnjy40b"/><path class="e_x53xaps"/><path class="g2yfshbdf"/><path class="bo51iypxr"/><path class="yp6x4sb1k"/><path class="lrlarebcg"/><path class="dxdpz6gbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:solar-system-duotone-bold" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dxdpz6gbz {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e_x53xaps {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12a6 6 0 1 1 -3 -5.2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g2yfshbdf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 19.79A9 9 0 1 1 21 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kllnjy40b {
  fill: currentColor;
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lrlarebcg {
  d: path("M16.5 19.79A9 9 0 1 1 21 12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yp6x4sb1k {
  d: path("M18 12a6 6 0 1 1 -3 -5.2");
}

</style>

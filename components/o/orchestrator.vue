<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="oa80gcjyx"/><path class="wy4yrcc5j"/><path class="hje9t-ban"/><circle class="l_77f6rkn"/><circle class="m79cmbb6o"/><circle class="f_r2wnagk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orchestrator" /></template>
<style>
.f_r2wnagk {
  cx: 18.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hje9t-ban {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v7.5m-6.75 0V14.5A1.75 1.75 0 0 1 7 12.75h10a1.75 1.75 0 0 1 1.75 1.75v2.25");
}

.l_77f6rkn {
  cx: 5.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m79cmbb6o {
  cx: 12px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oa80gcjyx {
  width: 8.5px;
  height: 6.5px;
  x: 7.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.wy4yrcc5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 6h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

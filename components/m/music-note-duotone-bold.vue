<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="m2pvlvbek"/><path class="hmv2wxw-k"/><path class="fitn60wtu"/><path class="ew7y79byi"/><path class="huj3g_bus"/><path class="xob7qnbfo"/><path class="nycbsrkgh"/><path class="wwbyt5bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-note-duotone-bold" /></template>
<style>
.ew7y79byi {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.f6q7r5bds {
  fill: currentColor;
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fitn60wtu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hmv2wxw-k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.huj3g_bus {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.krwm4ebpd {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m2pvlvbek {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nycbsrkgh {
  d: path("M17 17V5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wwbyt5bkd {
  d: path("M9 5h8");
}

.xob7qnbfo {
  d: path("M9 17V5");
}

</style>

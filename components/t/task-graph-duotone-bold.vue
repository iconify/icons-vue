<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gwjllcbqv"/><path class="fi2ffwb2u"/><path class="wi4c4ehou"/><path class="j9_v4lb9k"/><path class="oocx6nb0t"/><path class="yp_l0abrr"/><path class="fmr2g_bno"/><path class="hlnl_9cae"/><path class="llakqobuk"/><path class="nd30accfc"/><path class="e6tys9mkg"/><path class="nuz6-76is"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-graph-duotone-bold" /></template>
<style>
.e6tys9mkg {
  d: path("m7 16 4 -4");
}

.fi2ffwb2u {
  fill: currentColor;
  d: path("M3 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fmr2g_bno {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gwjllcbqv {
  fill: currentColor;
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hlnl_9cae {
  d: path("M3 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.j9_v4lb9k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.llakqobuk {
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nd30accfc {
  d: path("m7 8 4 4");
}

.nuz6-76is {
  d: path("M15 12h6");
}

.oocx6nb0t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wi4c4ehou {
  fill: currentColor;
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yp_l0abrr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

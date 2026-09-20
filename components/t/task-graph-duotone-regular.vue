<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gwjllcbqv"/><path class="fi2ffwb2u"/><path class="wi4c4ehou"/><path class="bmzr43bje"/><path class="fvl4b5b2y"/><path class="nx1eh8hxp"/><path class="fmr2g_bno"/><path class="hlnl_9cae"/><path class="llakqobuk"/><path class="nd30accfc"/><path class="e6tys9mkg"/><path class="nuz6-76is"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-graph-duotone-regular" /></template>
<style>
.bmzr43bje {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

.fvl4b5b2y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.llakqobuk {
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nd30accfc {
  d: path("m7 8 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuz6-76is {
  d: path("M15 12h6");
}

.nx1eh8hxp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wi4c4ehou {
  fill: currentColor;
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

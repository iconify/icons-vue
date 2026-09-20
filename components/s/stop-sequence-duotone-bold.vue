<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j93aodlin"/><path class="f3oxrjbrz"/><path class="unova7b3b"/><path class="imu-axb_c"/><path class="l2x-_sd5q"/><path class="xcjkf-bzr"/><path class="olmwgycdy"/><path class="l_9_psbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stop-sequence-duotone-bold" /></template>
<style>
.f3oxrjbrz {
  fill: currentColor;
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.imu-axb_c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j93aodlin {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l_9_psbce {
  d: path("M21 6v12");
}

.l2x-_sd5q {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.olmwgycdy {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.unova7b3b {
  fill: currentColor;
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xcjkf-bzr {
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

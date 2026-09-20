<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m20u53bzo"/><path class="tlah7acnn"/><path class="elo_ccj2r"/><path class="yz_nd208h"/><path class="qox9oe20g"/><path class="tjvfebbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tool-error-retry-duotone-bold" /></template>
<style>
.elo_ccj2r {
  d: path("M9 4v7");
}

.m20u53bzo {
  fill: currentColor;
  d: path("M6 13a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qox9oe20g {
  d: path("M9.5 14.5 12 12l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tjvfebbkf {
  d: path("M9.5 16.5 12 19l2.5 -2.5");
}

.tlah7acnn {
  d: path("M6 13a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.yz_nd208h {
  d: path("M15 4v7");
}

</style>

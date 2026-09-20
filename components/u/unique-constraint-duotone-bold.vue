<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7d56fjnv"/><path class="c07le3bhf"/><path class="vyks9vbfn"/><path class="rw6ho_bav"/><path class="fszcuob-o"/><path class="y1lnycw3l"/><path class="env2hib9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unique-constraint-duotone-bold" /></template>
<style>
.c07le3bhf {
  fill: currentColor;
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.env2hib9n {
  d: path("m15 13 4 4");
}

.fszcuob-o {
  d: path("M7 13v4");
}

.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.y1lnycw3l {
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

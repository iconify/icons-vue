<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aknqtcczd"/><path class="f1vpicczb"/><path class="o0-3vqblf"/><path class="qbkvt7bcg"/><path class="kkozh6bab"/><path class="iohczjr2d"/><path class="bcfe5ob8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-to-video-duotone-thin" /></template>
<style>
.aknqtcczd {
  fill: currentColor;
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bcfe5ob8i {
  d: path("M19 11v11");
}

.f1vpicczb {
  d: path("M2 4h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iohczjr2d {
  d: path("M14 11v11");
}

.kkozh6bab {
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

.o0-3vqblf {
  d: path("M2 8h8");
}

.qbkvt7bcg {
  d: path("m4 11.5 3 3 -3 3");
}

</style>

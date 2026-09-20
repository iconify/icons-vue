<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m8c8atiya"/><path class="bf4bqzbvb"/><path class="tart4iz-n"/><path class="n0n63pb2v"/><path class="p3mjlkbpz"/><path class="ij7rtuuan"/><path class="ayvbjgbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shared-memory-duotone-bold" /></template>
<style>
.ayvbjgbud {
  d: path("M10.5 8h3");
}

.bf4bqzbvb {
  fill: currentColor;
  d: path("M6.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ij7rtuuan {
  d: path("M13.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.m8c8atiya {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.p3mjlkbpz {
  d: path("M6.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tart4iz-n {
  fill: currentColor;
  d: path("M13.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

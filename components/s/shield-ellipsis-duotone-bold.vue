<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crzn5obfu"/><path class="zod8occdh"/><path class="qgk9g7b5k"/><path class="ih_fyab3i"/><path class="ymp2b4b6u"/><path class="tn82r2bsv"/><path class="drftkjb-q"/><path class="pdux64boo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shield-ellipsis-duotone-bold" /></template>
<style>
.crzn5obfu {
  fill: currentColor;
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.drftkjb-q {
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ih_fyab3i {
  fill: currentColor;
  d: path("M14.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pdux64boo {
  d: path("M14.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qgk9g7b5k {
  fill: currentColor;
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tn82r2bsv {
  d: path("M7.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

.zod8occdh {
  fill: currentColor;
  d: path("M7.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

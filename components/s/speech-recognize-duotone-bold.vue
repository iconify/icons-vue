<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mt0unbcuj"/><path class="bi-xw-w_y"/><path class="wk7r274wn"/><path class="m4acsfbpb"/><path class="xxobs597t"/><path class="nancp9ugm"/><path class="rgnpgnbjr"/><path class="fttf_kblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-recognize-duotone-bold" /></template>
<style>
.bi-xw-w_y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fttf_kblh {
  d: path("M16 14h5");
}

.m4acsfbpb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mt0unbcuj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nancp9ugm {
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
}

.rgnpgnbjr {
  d: path("M16 10h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wk7r274wn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xxobs597t {
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
}

</style>

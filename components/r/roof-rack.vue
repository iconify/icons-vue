<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tso9stbtp"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roof-rack" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0haxibzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tso9stbtp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5.75h9.5m-7 0v3m4-3v3M2.75 15.5V14q0-1.25 1.22-1.51l2.31-.48q1.22-.26 1.97-1.26l.75-1q.75-1 2-1h2.5q1.25 0 2 1l.75 1q.75 1 2 1.07l1.75.11q1.25.07 1.25 1.32v2.25q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25M8 11.75h8.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

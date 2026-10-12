<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="boicjebih"/><rect class="a-9sd_v4d"/><path class="ial852b4e"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sightseeing-bus" /></template>
<style>
.a-9sd_v4d {
  width: 18.5px;
  height: 9.25px;
  x: 2.75px;
  y: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.boicjebih {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5V5.25h12V7.5");
}

.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ial852b4e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.75h2.5V12H5Zm5.75 0h2.5V12h-2.5Zm5.75 0H19V12h-2.5Z");
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

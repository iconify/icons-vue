<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="y001kyeka"/><path class="n0uizqw5r"/><path class="eehfmvbwm"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:party-bus" /></template>
<style>
.eehfmvbwm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 3h.01M16 3h.01");
}

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

.n0uizqw5r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9h2.5v2.5h-2.5Zm5 0h2.5v2.5h-2.5Zm5 0h2.5v2.5h-2.5Z");
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

.y001kyeka {
  width: 18.5px;
  height: 10.75px;
  x: 2.75px;
  y: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

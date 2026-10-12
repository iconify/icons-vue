<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="gnq4yvbnv"/><circle class="qkd3rlb4c"/><rect class="m4hpm9b4f"/><path class="mjkp06bvk"/><path class="gy76-xb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sponge" /></template>
<style>
.gnq4yvbnv {
  cx: 7.5px;
  cy: 5.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gy76-xb2k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16.5h.01m3.99.25h.01m3.99-.5h.01");
}

.m4hpm9b4f {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.mjkp06bvk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.5h18.5");
}

.qkd3rlb4c {
  cx: 12.75px;
  cy: 4.5px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

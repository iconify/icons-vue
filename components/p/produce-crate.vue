<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zp1n3tbnd"/><circle class="ox6vyub6l"/><circle class="dyy5pkbxx"/><rect class="leq75q_mm"/><path class="y5g3ngb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:produce-crate" /></template>
<style>
.dyy5pkbxx {
  cx: 12px;
  cy: 6.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leq75q_mm {
  width: 18.5px;
  height: 8.25px;
  x: 2.75px;
  y: 13px;
  rx: 1.5px;
}

.ox6vyub6l {
  cx: 18.75px;
  cy: 8px;
  r: 2px;
}

.y5g3ngb6e {
  d: path("M2.75 17.25h18.5");
}

.zp1n3tbnd {
  cx: 5.25px;
  cy: 8px;
  r: 2px;
}

</style>

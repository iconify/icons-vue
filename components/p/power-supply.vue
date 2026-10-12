<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="bq7ynzh6o"/><path class="lqs531bhw"/><path class="w_8vmacqn"/><rect class="lx8-h2hgq"/><path class="gdter6leh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-supply" /></template>
<style>
.bq7ynzh6o {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.gdter6leh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 15.75h2.5");
}

.lqs531bhw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 7.75a4.25 4.25 0 1 1 0 8.5a4.25 4.25 0 1 1 0-8.5");
}

.lx8-h2hgq {
  width: 2.5px;
  height: 4px;
  x: 16px;
  y: 8px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.w_8vmacqn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

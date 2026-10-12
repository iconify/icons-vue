<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="kcjc1ybqv"/><path class="avw3v3b5c"/><rect class="u_tvd-bqj"/><path class="ah69srb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:virtual-card" /></template>
<style>
.ah69srb4f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 18.25h.01");
}

.avw3v3b5c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h15");
}

.kcjc1ybqv {
  width: 15px;
  height: 11px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.u_tvd-bqj {
  width: 7px;
  height: 10.5px;
  x: 14.25px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

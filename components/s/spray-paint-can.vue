<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ysi4bygqe"/><path class="kv-cijb2n"/><rect class="rd4e40bex"/><rect class="rccuv_71h"/><path class="aaaonzuou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spray-paint-can" /></template>
<style>
.aaaonzuou {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 4.25h.01m2.99-1h.01m-1.01 3.5h.01m3.24-.5h.01M20 9.75h.01");
}

.kv-cijb2n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.5h9");
}

.rccuv_71h {
  width: 3px;
  height: 3px;
  x: 7.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.rd4e40bex {
  width: 5.5px;
  height: 3.5px;
  x: 6px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ysi4bygqe {
  width: 9px;
  height: 12px;
  x: 4.25px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

</style>

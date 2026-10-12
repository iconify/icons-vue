<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f0ob_2b3h"/><path class="pw38xccef"/><path class="roxelobjv"/><path class="nz12qubkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:xss-script" /></template>
<style>
.f0ob_2b3h {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.nz12qubkf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 11L6 13.5L8.5 16m7-5l2.5 2.5l-2.5 2.5M13 10.5l-2 6");
}

.pw38xccef {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h18.5");
}

.roxelobjv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

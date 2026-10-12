<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><path class="xdg_s5hst"/></g><rect class="tk08jrbzk"/><path class="u46xc4iak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wifi-lock" /></template>
<style>
.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t_2lkqbxb {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tk08jrbzk {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.u46xc4iak {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

.xdg_s5hst {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.82 15.32a4.5 4.5 0 0 1 6.36 0m-9.54-3.18a9 9 0 0 1 12.72 0M2.81 9.31a13 13 0 0 1 18.38 0");
}

</style>

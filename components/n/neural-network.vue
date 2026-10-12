<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x82-9dbjm"/><circle class="vwl1wf1bw"/><circle class="tytpppbsp"/><circle class="e9-7-8-2z"/><circle class="h_tsn8bxt"/><circle class="rip_g9cqu"/><circle class="l33zoes5a"/><circle class="d81f_o4pi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:neural-network" /></template>
<style>
.d81f_o4pi {
  cx: 19px;
  cy: 17px;
  r: 2px;
}

.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l33zoes5a {
  cx: 19px;
  cy: 7px;
  r: 2px;
}

.rip_g9cqu {
  cx: 12px;
  cy: 19.25px;
  r: 2px;
}

.tytpppbsp {
  cx: 5px;
  cy: 17px;
  r: 2px;
}

.vwl1wf1bw {
  cx: 5px;
  cy: 7px;
  r: 2px;
}

.x82-9dbjm {
  d: path("m6.9 6.39l3.2-1.03m-3.47 2.8l3.74 2.68m-3.74 5l3.74-2.68M6.9 17.61l3.2 1.03m3.8-13.28l3.2 1.03m-3.2 12.25l3.2-1.03");
}

</style>

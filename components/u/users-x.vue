<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><circle class="y-aluxb2e"/><path class="l0cbzabqo"/></g><path class="f35xrjbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:users-x" /></template>
<style>
.f35xrjbjk {
  d: path("m15.25 15.25l4.5 4.5m0-4.5l-4.5 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.l0cbzabqo {
  d: path("M3.5 20.25h11a.75.75 0 0 0 .75-.75c0-2.9-2.7-5-6.25-5s-6.25 2.1-6.25 5a.75.75 0 0 0 .75.75M15 4.5a3.5 3.5 0 0 1 0 7m2.5 3.25c2.15.6 3.75 2.2 3.75 4.25v.5a.75.75 0 0 1-.75.75H19");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y-aluxb2e {
  cx: 9px;
  cy: 8px;
  r: 3.5px;
}

</style>

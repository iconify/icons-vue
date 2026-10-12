<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><path class="hgt0rccex"/></g><path class="upeuobe7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ticket-x" /></template>
<style>
.hgt0rccex {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75a2 2 0 0 1 2-2h14.5a2 2 0 0 1 2 2V9.5a2.5 2.5 0 0 0 0 5v1.75a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2V14.5a2.5 2.5 0 0 0 0-5Z");
}

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

.upeuobe7x {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 15.25l4.5 4.5m0-4.5l-4.5 4.5");
}

</style>

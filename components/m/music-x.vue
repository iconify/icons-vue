<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="yymvhuctj"/><circle class="xe95m5bil"/></g><path class="f35xrjbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:music-x" /></template>
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

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xe95m5bil {
  cx: 6.25px;
  cy: 17.25px;
  r: 2.75px;
}

.yymvhuctj {
  d: path("M9 17.25V6.35a1 1 0 0 1 .8-.98l9.5-1.9a1 1 0 0 1 1.2.98v10.8");
}

</style>

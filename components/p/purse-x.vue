<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="woiz9xxpb"/><path class="ht_-hsp_k"/></g><path class="f35xrjbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:purse-x" /></template>
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

.ht_-hsp_k {
  d: path("M7.75 9.25v-2a4.25 4.25 0 0 1 8.5 0v2m-6 4h3.5");
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

.woiz9xxpb {
  d: path("M6.25 9.25h11.5a2 2 0 0 1 1.95 1.55l1.5 7.5a2.5 2.5 0 0 1-2.45 2.95H5.25A2.5 2.5 0 0 1 2.8 18.3l1.5-7.5a2 2 0 0 1 1.95-1.55");
}

</style>

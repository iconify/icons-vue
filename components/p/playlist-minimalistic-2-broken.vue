<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ltwq23bbr"/><path class="z4exszsav"/><path class="fbnn_3bad"/><circle class="gvyc-o7fz"/><path class="rgnmckb3y"/><path class="bv2ncrb-z"/><path class="u9kct68nj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-2-broken" /></template>
<style>
.bv2ncrb-z {
  d: path("M3 6H10.4118M13.4118 6H15");
}

.fbnn_3bad {
  d: path("M17 16.5V12.5V8");
}

.gvyc-o7fz {
  cx: 14.5px;
  cy: 16.5px;
  r: 2.5px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltwq23bbr {
  d: path("M9 14H3");
}

.rgnmckb3y {
  d: path("M21 12C18.7909 12 17 10.2091 17 8");
}

.u9kct68nj {
  d: path("M13 10L6.82353 10M4.32353 10H3");
}

.z4exszsav {
  d: path("M8 18H3");
}

</style>

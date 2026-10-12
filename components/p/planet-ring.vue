<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="d3_y9bbtb"/><path class="fe_-7kb8v"/><path class="e32l6xbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:planet-ring" /></template>
<style>
.d3_y9bbtb {
  cx: 12px;
  cy: 12px;
  r: 5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.e32l6xbxm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 4.75h.01");
}

.fe_-7kb8v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 1.75 0 0 0 18.5 0m-18.5 0A9.25 1.75 0 0 1 5 10.86M21.25 12A9.25 1.75 0 0 0 19 10.86");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

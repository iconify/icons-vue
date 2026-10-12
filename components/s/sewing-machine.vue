<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pnppikvqm"/><rect class="uofemc_xz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sewing-machine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnppikvqm {
  d: path("M5 4.25h14.5q1.25 0 1.25 1.25v9.75q0 1.25-1.25 1.25h-2q-1.25 0-1.25-1.25v-4.5q0-1.25-1.25-1.25H8.75q-1.25 0-1.25 1t-1.25 1H5q-1.25 0-1.25-1.25V5.5q0-1.25 1.25-1.25m.5 7.25V16m13-9.25v7.5");
}

.uofemc_xz {
  width: 18.5px;
  height: 2.5px;
  x: 2.75px;
  y: 18.75px;
  rx: 1.25px;
}

</style>

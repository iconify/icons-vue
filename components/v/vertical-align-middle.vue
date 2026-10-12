<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wbbb3na8m"/><rect class="e9rnpc6cn"/><path class="ijs0p36kx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vertical-align-middle" /></template>
<style>
.e9rnpc6cn {
  width: 5px;
  height: 9px;
  x: 13.75px;
  y: 7.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijs0p36kx {
  d: path("M2.75 12h18.5");
}

.wbbb3na8m {
  width: 5px;
  height: 15.5px;
  x: 5.25px;
  y: 4.25px;
  rx: 1.5px;
}

</style>

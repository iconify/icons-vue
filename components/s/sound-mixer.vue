<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qzkvbx_uy"/><rect class="d1ap3nbxk"/><rect class="nxs8k4bae"/><rect class="bwndkobim"/><path class="sq1amlkms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sound-mixer" /></template>
<style>
.bwndkobim {
  width: 3px;
  height: 2.5px;
  x: 15.5px;
  y: 9.25px;
  rx: 0.75px;
}

.d1ap3nbxk {
  width: 3px;
  height: 2.5px;
  x: 5.5px;
  y: 8.75px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxs8k4bae {
  width: 3px;
  height: 2.5px;
  x: 10.5px;
  y: 12.75px;
  rx: 0.75px;
}

.qzkvbx_uy {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

.sq1amlkms {
  d: path("M7 7v1.75m0 2.5V17m5-10v5.75m0 2.5V17m5-10v2.25m0 2.5V17");
}

</style>

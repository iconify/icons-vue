<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="syxmtqd-u"/><path class="qku6atb4g"/><rect class="lbpz7v40p"/><rect class="s1_z59bmw"/><path class="eh0jr5bay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waiting-room" /></template>
<style>
.eh0jr5bay {
  d: path("M2.75 18h18.5M5 18v3.25M19 18v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lbpz7v40p {
  width: 7px;
  height: 6.5px;
  x: 3.25px;
  y: 11.5px;
  rx: 1.5px;
}

.qku6atb4g {
  d: path("M17.5 4.5V6l1 1");
}

.s1_z59bmw {
  width: 7px;
  height: 6.5px;
  x: 13.75px;
  y: 11.5px;
  rx: 1.5px;
}

.syxmtqd-u {
  cx: 17.5px;
  cy: 6px;
  r: 3.25px;
}

</style>

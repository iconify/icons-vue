<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ew68babsr"/><path class="eca6l-a7l"/><circle class="xd6dk168z"/><path class="y60bg5_ln"/><circle class="b36niz7vv"/><path class="sw9n0zb5s"/><rect class="tt-1aob6r"/><path class="ctwjpc5en"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:town-meeting" /></template>
<style>
.b36niz7vv {
  cx: 12px;
  cy: 7.75px;
  r: 2.25px;
}

.ctwjpc5en {
  d: path("M5.5 18v3.25m13-3.25v3.25");
}

.eca6l-a7l {
  d: path("M2.75 15.75a2.75 2.75 0 0 1 5.5 0Z");
}

.ew68babsr {
  cx: 5.5px;
  cy: 8.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sw9n0zb5s {
  d: path("M9 15.75a3 3 0 0 1 6 0Z");
}

.tt-1aob6r {
  width: 18.5px;
  height: 2.25px;
  x: 2.75px;
  y: 15.75px;
  rx: 1px;
}

.xd6dk168z {
  cx: 18.5px;
  cy: 8.75px;
  r: 2px;
}

.y60bg5_ln {
  d: path("M15.75 15.75a2.75 2.75 0 0 1 5.5 0Z");
}

</style>

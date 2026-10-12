<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p05m1bklz"/><path class="leai18bvc"/><circle class="c3v--mbkg"/><circle class="jcu4obbro"/><path class="fgbcr1izh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spelling-bee" /></template>
<style>
.c3v--mbkg {
  cx: 15.29px;
  cy: 5.6px;
  r: 1.25px;
}

.fgbcr1izh {
  d: path("M15.4 9a3 1.75-30 0 1 5.2-3a3 1.75-30 0 1-5.2 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcu4obbro {
  cx: 17.71px;
  cy: 4.2px;
  r: 1.25px;
}

.leai18bvc {
  d: path("m5.75 18.75l2.75-6.5l2.75 6.5m-4.3-2.25h3.1");
}

.p05m1bklz {
  width: 11.5px;
  height: 11.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 2px;
}

</style>

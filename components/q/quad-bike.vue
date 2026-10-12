<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le-tgqb6g"/><rect class="rew6l06mf"/><path class="n_dwmpbcu"/><circle class="uqtm_0bwt"/><circle class="kpq69ek8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quad-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpq69ek8f {
  cx: 18px;
  cy: 17.25px;
  r: 3px;
}

.le-tgqb6g {
  d: path("M2.75 13.75v-.5q0-.75.61-1.19l1.53-1.12q.61-.44 1.36-.44h11.5q.75 0 1.36.44l1.53 1.12q.61.44.61 1.19v.5q0 .75-.75.75h-17q-.75 0-.75-.75");
}

.n_dwmpbcu {
  d: path("m15.5 10.5l1-4h2");
}

.rew6l06mf {
  width: 5.5px;
  height: 2.5px;
  x: 7.25px;
  y: 8px;
  rx: 1px;
}

.uqtm_0bwt {
  cx: 6px;
  cy: 17.25px;
  r: 3px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-t_rcb_j"/><path class="ncssw1bmg"/><path class="ytn6n5dnm"/><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="acx2mjbnt"/><path class="rvw184bua"/><path class="heonuib3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:split-payment-duotone-thin" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.f-t_rcb_j {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.heonuib3n {
  d: path("M14.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ncssw1bmg {
  fill: currentColor;
  d: path("M7.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.rvw184bua {
  d: path("M7.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ytn6n5dnm {
  fill: currentColor;
  d: path("M14.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

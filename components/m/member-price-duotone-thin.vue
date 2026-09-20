<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-t_rcb_j"/><path class="qp569prdc"/><path class="m2jo8huiy"/><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="qr0eduups"/><path class="fh1okhbsq"/><path class="qzs5rhb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:member-price-duotone-thin" /></template>
<style>
.f-t_rcb_j {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fh1okhbsq {
  d: path("m9 17 6 -6");
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

.m2jo8huiy {
  fill: currentColor;
  d: path("M13.5 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.qp569prdc {
  fill: currentColor;
  d: path("M8.5 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qr0eduups {
  d: path("M8.5 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qzs5rhb5h {
  d: path("M13.5 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

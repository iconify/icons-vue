<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ivoeacboo"/><path class="vens5qb4j"/><path class="ahqm1w_st"/><circle class="wzg4aubzr"/><circle class="sytsq3bno"/><circle class="if8vxw0yd"/><circle class="qhwxsn1ug"/><circle class="tg6zzec8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openstable" /></template>
<style>
.ahqm1w_st {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.66 7.15C14.32 4.24 18.96 2.5 24 2.5s9.68 1.74 13.34 4.65m0 33.7c-3.66 2.91-8.3 4.65-13.34 4.65s-9.68-1.74-13.34-4.65m-3.51-3.51C4.24 33.68 2.5 29.04 2.5 24s1.74-9.68 4.65-13.34m33.7 26.68c2.91-3.66 4.65-8.3 4.65-13.34s-1.74-9.68-4.65-13.34m-23.686 6.504l-4-4m0 21.675l4-4m13.672-13.675l4-4m0 21.675l-4-4");
}

.if8vxw0yd {
  cx: 39.203px;
  cy: 8.797px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ivoeacboo {
  cx: 24px;
  cy: 24px;
  r: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qhwxsn1ug {
  cx: 8.797px;
  cy: 8.797px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sytsq3bno {
  cx: 8.797px;
  cy: 39.203px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tg6zzec8l {
  cx: 39.203px;
  cy: 39.203px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vens5qb4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l8.836 12.664L45.5 24l-12.661 8.839L24 45.5l-8.836-12.664L2.5 24l12.664-8.836z");
}

.wzg4aubzr {
  cx: 24px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

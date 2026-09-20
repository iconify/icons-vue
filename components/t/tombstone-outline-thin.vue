<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgrfb-bqu"/><path class="qnmmmsbha"/><path class="klk7mdb2c"/><path class="h0co0sh-j"/><path class="ys-dg812g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tombstone-outline-thin" /></template>
<style>
.h0co0sh-j {
  d: path("m20.5 9.5 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klk7mdb2c {
  d: path("m17.5 9.5 3 3");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>

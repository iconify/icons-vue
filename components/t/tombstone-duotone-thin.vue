<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="uzf676bdq"/><path class="d1vyqwbic"/><path class="jcxkzijlc"/><path class="yd1dd2b-v"/><path class="xgrfb-bqu"/><path class="qnmmmsbha"/><path class="klk7mdb2c"/><path class="h0co0sh-j"/><path class="ys-dg812g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tombstone-duotone-thin" /></template>
<style>
.d1vyqwbic {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17.5 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

.jcxkzijlc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20.5 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.klk7mdb2c {
  d: path("m17.5 9.5 3 3");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.uzf676bdq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>

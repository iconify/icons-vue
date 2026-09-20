<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mypzt1bhf"/><path class="iwqknw80c"/><path class="ert_saboi"/><path class="e2se01bcv"/><path class="qw94a7xnn"/><path class="n0hr0gbrt"/><path class="jcxg2bbvb"/><path class="i50mf1njm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:webhook-in-duotone-thin" /></template>
<style>
.e2se01bcv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ert_saboi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i50mf1njm {
  d: path("m7 9 3 3 -3 3");
}

.iwqknw80c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 6.8a6 6 0 1 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.mypzt1bhf {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0hr0gbrt {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qw94a7xnn {
  d: path("M13 6.8a6 6 0 1 1 0 10.4");
}

</style>

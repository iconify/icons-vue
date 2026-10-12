<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="a_3y1e_gc"/><path class="cueqsyb3v"/><path class="tq0y9obbf"/><path class="ir7uqfb2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:new-year-clock" /></template>
<style>
.a_3y1e_gc {
  cx: 11.5px;
  cy: 13.75px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.cueqsyb3v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 13.75v-5m0 5V10");
}

.ir7uqfb2s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.31 7.28l2.13 1.79q.46.38.67-.18l1.93-5.08q.21-.56-.29-.22l-4.4 2.97q-.5.34-.04.72");
}

.tq0y9obbf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 13.75h.01m-5.01 5h.01m-5.01-5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

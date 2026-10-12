<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gyhtaq2xk"/><path class="t4fshhb2g"/><path class="ecl_f959t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mountain-hut" /></template>
<style>
.ecl_f959t {
  d: path("M10.75 21.25v-3h2.5v3");
}

.gyhtaq2xk {
  d: path("m2.75 16.5l5.5-10l3.25 4.75l2.5-3.5l7.25 9.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4fshhb2g {
  d: path("M7.5 20.25V17.5q0-1 .77-1.64l2.96-2.47q.77-.64 1.54 0l2.96 2.47q.77.64.77 1.64v2.75q0 1-1 1h-7q-1 0-1-1");
}

</style>

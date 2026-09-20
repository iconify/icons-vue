<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oyxdwu0be"/><path class="c4o3x9bhp"/><path class="a97qfmbix"/><path class="f2vh026ub"/><path class="uadefenvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:network-policy-outline-bold" /></template>
<style>
.a97qfmbix {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.c4o3x9bhp {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.f2vh026ub {
  d: path("M10 9h4");
}

.oyxdwu0be {
  d: path("M15 3h5v8l-8 8 -8 -8V3h5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uadefenvd {
  d: path("M7 22h10");
}

</style>

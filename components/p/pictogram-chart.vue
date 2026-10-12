<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xhnw9ebpu"/><path class="at9kq0j5d"/><circle class="p98yu_b-b"/><path class="csy7pebya"/><circle class="r7064rbil"/><path class="nh2lh_b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pictogram-chart" /></template>
<style>
.at9kq0j5d {
  d: path("M2.75 18.5v-4.75a2.25 2.25 0 0 1 4.5 0v4.75a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1");
}

.csy7pebya {
  d: path("M9.75 18.5v-4.75a2.25 2.25 0 0 1 4.5 0v4.75a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nh2lh_b0n {
  d: path("M16.75 18.5v-4.75a2.25 2.25 0 0 1 4.5 0v4.75a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1");
}

.p98yu_b-b {
  cx: 12px;
  cy: 7.75px;
  r: 1.75px;
}

.r7064rbil {
  cx: 19px;
  cy: 7.75px;
  r: 1.75px;
}

.xhnw9ebpu {
  cx: 5px;
  cy: 7.75px;
  r: 1.75px;
}

</style>

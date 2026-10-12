<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pocksj24m"/><circle class="a56ludvdj"/><circle class="imf88e1vk"/><circle class="i093j3bwh"/><path class="dfdvn3yjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-chart" /></template>
<style>
.a56ludvdj {
  cx: 4px;
  cy: 19.5px;
  r: 1.25px;
}

.dfdvn3yjb {
  d: path("M18 2.75q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i093j3bwh {
  cx: 13.5px;
  cy: 16px;
  r: 1.25px;
}

.imf88e1vk {
  cx: 8px;
  cy: 11px;
  r: 1.25px;
}

.pocksj24m {
  d: path("m4.85 17.69l2.3-4.88m2.33-.46l2.54 2.3m2.3-.47l1.32-2.94");
}

</style>

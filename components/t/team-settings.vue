<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="r3pmgdciu"/><path class="ztek7xgqb"/><circle class="fe845acww"/><circle class="qyx1q-b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:team-settings" /></template>
<style>
.fe845acww {
  cx: 16.75px;
  cy: 14.75px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyx1q-b5s {
  cx: 19.75px;
  cy: 18.5px;
  r: 1.25px;
}

.r3pmgdciu {
  cx: 8.25px;
  cy: 8px;
  r: 3.5px;
}

.ztek7xgqb {
  d: path("M3.5 20.25H13a.75.75 0 0 0 .75-.75c0-2.9-2.45-5-5.5-5s-5.5 2.1-5.5 5a.75.75 0 0 0 .75.75M14.25 4a3.5 3.5 0 0 1 0 7m2.5 1.75v.75m0 2.5v5.25m3-8.5v4.5m0 2.5v1.5");
}

</style>

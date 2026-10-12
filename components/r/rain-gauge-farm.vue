<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bqaishviv"/><rect class="ypc83mbgz"/><path class="wxw-yklwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rain-gauge-farm" /></template>
<style>
.bqaishviv {
  d: path("M7.1 2.75h9.8q.6 0 .22.46l-2.74 3.33Q14 7 13.4 7h-2.8q-.6 0-.98-.46L6.88 3.21q-.38-.46.22-.46");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxw-yklwv {
  d: path("M9.5 11h2m-2 3h2m-2 3h2M5 10c.75 1 1.25 1.75 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.5 1.25-2.5m14 3c.75 1 1.25 1.75 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.5 1.25-2.5");
}

.ypc83mbgz {
  width: 5px;
  height: 14.25px;
  x: 9.5px;
  y: 7px;
  rx: 1.5px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o2tws2j4q"/><circle class="qhvrk_ymv"/><path class="sqcb-fb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-slot" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2tws2j4q {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 6px;
  rx: 2.5px;
}

.qhvrk_ymv {
  cx: 8.25px;
  cy: 12px;
  r: 3px;
}

.sqcb-fb9g {
  d: path("M8.25 10.5V12l1 .75m5-2.5h3.5m-3.5 3.5h2");
}

</style>

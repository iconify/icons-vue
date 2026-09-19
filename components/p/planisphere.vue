<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xul6iebrm"/><circle class="h8vvclbvn"/><circle class="rsla9p5fx"/><circle class="qva93qm6t"/><circle class="vxu833y3m"/><circle class="jdpe3z90m"/><circle class="pfv9gbbhm"/><path class="l33ns8bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:planisphere" /></template>
<style>
.h8vvclbvn {
  cx: 20.629px;
  cy: 24.642px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jdpe3z90m {
  cx: 41.75px;
  cy: 26.875px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l33ns8bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.356 24.915a29 29 0 0 0 3.978.03M14.55 23.54a44 44 0 0 0 4.339.955M7.48 28.231l4.124-4.02m17.011 2.088l1.418 3.882m10.838-12.265l.707 7.209m-9.347 5.989l7.922-3.528m-.907-10.437l-9.736 6.519");
}

.pfv9gbbhm {
  cx: 40.7px;
  cy: 16.175px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qva93qm6t {
  cx: 30.633px;
  cy: 31.825px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rsla9p5fx {
  cx: 28.056px;
  cy: 24.642px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vxu833y3m {
  cx: 6.25px;
  cy: 29.475px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xul6iebrm {
  cx: 12.883px;
  cy: 23.018px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

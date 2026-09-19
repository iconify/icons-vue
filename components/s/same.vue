<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="knhvbv-9j"/><circle class="qh7nu6jxk"/><circle class="q68us0_wj"/><circle class="k4ywcdn8t"/><circle class="pr8i2q0tg"/><circle class="pisguhbwo"/><circle class="efs7-lbsq"/><circle class="jmi04kbqt"/><circle class="rj9ny3z-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:same" /></template>
<style>
.efs7-lbsq {
  cx: 10.546px;
  cy: 37.455px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jmi04kbqt {
  cx: 24px;
  cy: 37.455px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k4ywcdn8t {
  cx: 10.546px;
  cy: 24px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.knhvbv-9j {
  cx: 10.546px;
  cy: 10.546px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pisguhbwo {
  cx: 37.455px;
  cy: 24px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pr8i2q0tg {
  cx: 24px;
  cy: 24px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q68us0_wj {
  cx: 37.455px;
  cy: 10.546px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qh7nu6jxk {
  cx: 24px;
  cy: 10.546px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rj9ny3z-o {
  cx: 37.455px;
  cy: 37.455px;
  r: 5.045px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

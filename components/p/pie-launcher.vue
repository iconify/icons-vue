<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rl1r2r-ma"/><circle class="hejaygcep"/><circle class="gc9nzwunz"/><circle class="jldolvn2h"/><circle transform="rotate(-.439 29.78 7.645)" class="eyjb_bb8a"/><circle class="km2y-99eq"/><circle class="p6mp0vbvs"/><circle class="m-s11dice"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pie-launcher" /></template>
<style>
.eyjb_bb8a {
  cx: 29.78px;
  cy: 7.643px;
  r: 4.025px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gc9nzwunz {
  cx: 18.006px;
  cy: 39.225px;
  r: 5.157px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hejaygcep {
  cx: 39.343px;
  cy: 18.63px;
  r: 5.157px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jldolvn2h {
  cx: 7.525px;
  cy: 29.494px;
  r: 4.025px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.km2y-99eq {
  cx: 18.253px;
  cy: 7.045px;
  r: 2.893px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m-s11dice {
  cx: 11.258px;
  cy: 11.435px;
  r: 1.761px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p6mp0vbvs {
  cx: 7.016px;
  cy: 18.356px;
  r: 2.893px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rl1r2r-ma {
  cx: 34.957px;
  cy: 35.322px;
  r: 6.289px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

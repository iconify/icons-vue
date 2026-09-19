<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sq4azbbzh"/><path class="yvz3m05yr"/><circle class="vngyc8w4p"/><circle class="ed0wm3j9i"/><circle class="lu2icfbbj"/><circle class="i0lwo028i"/><circle class="rpg6zpbau"/><circle class="iolkoubgb"/><circle class="bp2wruxin"/><circle class="mp_3c2voa"/><circle class="aoxn0abbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weather-forecast" /></template>
<style>
.aoxn0abbk {
  cx: 14.126px;
  cy: 42.194px;
  r: 0.75px;
  fill: currentColor;
}

.bp2wruxin {
  cx: 34.493px;
  cy: 41.444px;
  r: 0.75px;
  fill: currentColor;
}

.ed0wm3j9i {
  cx: 28.431px;
  cy: 39.625px;
  r: 0.75px;
  fill: currentColor;
}

.i0lwo028i {
  cx: 11.961px;
  cy: 34.842px;
  r: 0.75px;
  fill: currentColor;
}

.iolkoubgb {
  cx: 37.653px;
  cy: 34.036px;
  r: 0.75px;
  fill: currentColor;
}

.lu2icfbbj {
  cx: 30.495px;
  cy: 34.735px;
  r: 0.75px;
  fill: currentColor;
}

.mp_3c2voa {
  cx: 34.063px;
  cy: 36.917px;
  r: 0.75px;
  fill: currentColor;
}

.rpg6zpbau {
  cx: 17.898px;
  cy: 37.712px;
  r: 0.75px;
  fill: currentColor;
}

.sq4azbbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.692 31.156h-8.627c-9.018-.804-8.97-13.994.054-14.736c1.655-6.32 6.642-9.082 11.436-8.824a10.9 10.9 0 0 1 9.178 5.868c11.254 1.935 9.9 16.359 0 17.692h-9.186");
}

.vngyc8w4p {
  cx: 17.457px;
  cy: 33.649px;
  r: 0.75px;
  fill: currentColor;
}

.yvz3m05yr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.048 8.714a6.685 6.685 0 1 0-9.44 8.697m15.542 7.954l-4.729 8.684l3.13 1.586l-1.35 6.559l5.22-7.73l-3.048-1.63Z");
}

</style>

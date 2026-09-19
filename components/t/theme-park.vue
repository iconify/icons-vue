<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gzhkaubid"/><rect class="aq7f6ub9n"/><circle class="c98l4_bcv"/><circle class="ojt8q52gq"/><rect class="qoarp0bdc"/><circle class="e22w6gjba"/><circle class="wwhm2b3is"/><path class="r95e1veox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:theme-park" /></template>
<style>
.aq7f6ub9n {
  width: 11.784px;
  height: 11.784px;
  x: 30.385px;
  y: 6.019px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.859px;
  ry: 2.859px;
}

.c98l4_bcv {
  cx: 33.88px;
  cy: 9.947px;
  r: 0.75px;
  fill: currentColor;
}

.e22w6gjba {
  cx: 10.081px;
  cy: 31.294px;
  r: 0.75px;
  fill: currentColor;
}

.gzhkaubid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.982 17.258c.641 1.849.99 3.835.99 5.903c0 6.234-3.169 11.727-7.984 14.957m-27.073-9.2a18 18 0 0 1-.94-5.757c0-9.94 8.058-17.999 17.998-17.999c2.63 0 5.128.564 7.38 1.578M21.105 27.481a5.185 5.185 0 1 1 5.784-.032");
}

.ojt8q52gq {
  cx: 38.674px;
  cy: 9.947px;
  r: 0.75px;
  fill: currentColor;
}

.qoarp0bdc {
  width: 11.784px;
  height: 11.784px;
  x: 6.587px;
  y: 27.366px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.859px;
  ry: 2.859px;
}

.r95e1veox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.341 39.15l-1.516 2.279c-.778 1.169.06 2.733 1.465 2.733h21.436c1.405 0 2.243-1.564 1.465-2.733l-10.718-16.11a1.76 1.76 0 0 0-2.93 0l-4.173 6.273m5.603-13.616V5.169m5.185 17.992h12.814m-23.184 0H5.974");
}

.wwhm2b3is {
  cx: 14.876px;
  cy: 31.294px;
  r: 0.75px;
  fill: currentColor;
}

</style>

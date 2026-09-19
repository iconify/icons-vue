<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_i8820zz"/><circle class="cpk0fnbgt"/><path class="id1-53wmd"/><circle class="shb1lxbmy"/><circle class="fzcwwqbay"/><path class="kxwz3gbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbb-cint-customer-app" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fzcwwqbay {
  cx: 27.16px;
  cy: 32.54px;
  r: 0.75px;
  fill: currentColor;
}

.id1-53wmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.421 15.318h39.158m-21.601 6.557h4.154a3.915 3.915 0 0 1 3.915 3.915v9.507h0h-11.984h0V25.79a3.915 3.915 0 0 1 3.915-3.915m-2.909-2.183h9.862m-5.439 2.183l-1.7-2.183m2.716 2.183l1.7-2.183m-8.145 10.261h11.984m-8.096-5.271h4.208");
}

.kxwz3gbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.063 37.759h11.984m-13.571 2.65h15.048m-11.402-5.118l-2.848 5.112m10.575-5.112l2.849 5.112");
}

.shb1lxbmy {
  cx: 20.84px;
  cy: 32.54px;
  r: 0.75px;
  fill: currentColor;
}

.z_i8820zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.87 6.041l2.865 2.868l-2.867 2.867m-5.739 0L18.265 8.91l2.867-2.868m-2.867 2.867h11.47M24 6.041v5.736");
}

</style>

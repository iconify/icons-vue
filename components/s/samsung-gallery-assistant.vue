<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4oi40gxm"/><circle class="u9fwj3bhl"/><circle class="spk43i59q"/><path class="r_6qglp5b"/><circle class="oypf5vf2l"/><path class="ucw583bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-gallery-assistant" /></template>
<style>
.m4oi40gxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 26.996v10.5m0-31.5v10");
}

.oypf5vf2l {
  cx: 31.136px;
  cy: 16.715px;
  r: 2.179px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_6qglp5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.496h-7.5m26 0H35");
}

.spk43i59q {
  cx: 29.5px;
  cy: 37.496px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u9fwj3bhl {
  cx: 11px;
  cy: 21.496px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ucw583bmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.731 15.05c-.408-.686-2.433-3.935-4.734-5.263a2.93 2.93 0 0 0-2.93 5.074c2.365 1.365 6.123 1.46 6.93 1.464m2.873-1.663c.391-.7 2.196-4.073 2.196-6.729a2.93 2.93 0 1 0-5.86 0c0 2.737 1.798 6.033 2.193 6.725m2.879 1.661c.813-.012 4.633-.133 6.928-1.457a2.93 2.93 0 0 0-2.93-5.075c-2.371 1.369-4.335 4.576-4.734 5.261m0 3.332c.408.685 2.433 3.934 4.734 5.263a2.93 2.93 0 0 0 2.93-5.075c-2.365-1.365-6.119-1.46-6.926-1.464m-2.876 1.666c-.39.699-2.198 4.07-2.198 6.726a2.93 2.93 0 1 0 5.86 0c0-2.736-1.807-6.035-2.203-6.727m-2.87-1.659c-.812.012-4.631.133-6.926 1.458a2.93 2.93 0 0 0 2.93 5.075c2.371-1.37 4.331-4.582 4.73-5.267");
}

</style>

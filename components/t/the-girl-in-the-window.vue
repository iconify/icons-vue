<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="z2vi7cj8j"/><circle class="s59mrebve"/><path class="v_gt9q_wi"/><path class="zvy6_hbid"/><path class="a_wi-lbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-girl-in-the-window" /></template>
<style>
.a_wi-lbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.443 28.853c.663-.513 1.326-1.026 1.917-1.703c.59-.677 1.108-1.518 1.626-2.36");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s59mrebve {
  cx: 27.317px;
  cy: 40.986px;
  r: 0.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v_gt9q_wi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.138 18.777l2.132-.159m-1.485.111c.04.506.08 1.013.518 1.484c.438.47 1.273.906 1.943 1.009c.669.103 1.171-.126 1.673-.356m-4.549.501c.193.242.386.484.825.688s1.123.37 1.56.434s.629.027.82-.01m-5.323-7.64c-.11 3.412-.221 6.825-.252 9.16s.017 3.595.065 4.854m.042 5.261c-.103 2.298-.207 4.596-.115 6.493c.092 1.896.38 3.39.667 4.883m-.691-7.61l1.776-2.73");
}

.z2vi7cj8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.588 4.214v39.363M11.451 6.542v34.916m-6.424-7.345h37.946m-39.489-5.26h41.46m-20.952-2.941l2.323.03M24 24l1.103-.08m11.536 4.933c-.313-.913-.625-1.825-.747-4.42c-.122-2.596-.054-6.875-.104-10.005s-.218-5.111-.717-6.585c-.5-1.475-1.33-2.442-2.16-3.41m-17.322 6.853c.256-1.222.512-2.443 1.077-3.808s1.44-2.875 2.314-4.384m16.546 31.02c.042 1.88.084 3.76.22 5.009c.137 1.248.368 1.863.6 2.48m1.75-7.489c.594.428 1.188.856 1.589 1.374s.608 1.126.815 1.734M25.744 35.15c-.055 1.658-.11 3.316.055 5.012c.166 1.696.552 3.43.94 5.163m2.653-2.258l1.955-2.613m-5.603-5.304l2.031 3.979l3.541-3.235");
}

.zvy6_hbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.252 14.839c1.34 1.26 2.679 2.52 3.811 3.464s2.06 1.575 2.523 2.064s.463.838.443 1.986s-.062 3.097-.055 4.313c.007 1.217.062 1.702.117 2.187m.373 5.261c-.05.593-.099 1.187-.14 2.057a59 59 0 0 0-.07 2.778c.005.76.048 1.133.1 1.934s.108 2.03.166 3.259");
}

</style>

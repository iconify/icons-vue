<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xnabd2ntw"/><circle class="g9-_f81af"/><circle class="l_o3c0b4w"/><path class="ta5tin_jd"/><circle class="z8mvggc6s"/><path class="xt9-6jbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photo-roulette" /></template>
<style>
.g9-_f81af {
  cx: 24px;
  cy: 35.824px;
  r: 1.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.l_o3c0b4w {
  cx: 15.293px;
  cy: 37.273px;
  r: 1.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ta5tin_jd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.89 42.15c.31-.26.51-.66.51-1.1c0-.8-.65-1.45-1.45-1.45c-.44 0-.84.2-1.1.51m3.525-4.717l3.554 7.107m6.032-9.603l1.574 9.603");
}

.xnabd2ntw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.538 29.325V14.817h4.75c2.684 0 4.861 2.181 4.861 4.872s-2.177 4.873-4.862 4.873h-4.75m13.313 4.763V14.817h4.75c2.686 0 4.862 2.181 4.862 4.872s-2.177 4.873-4.862 4.873h-4.75m4.75 0l4.75 4.759M5.5 37.21c5.51-2.96 11.81-4.63 18.5-4.63s12.99 1.67 18.5 4.63");
}

.xt9-6jbyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.15 40.11a1.44 1.44 0 0 0-1.1-.51c-.8 0-1.45.65-1.45 1.45c0 .44.2.84.51 1.1m-1.485-6.757L35.071 42.5m-6.032-9.603L27.465 42.5");
}

.z8mvggc6s {
  cx: 32.707px;
  cy: 37.273px;
  r: 1.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

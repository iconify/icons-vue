<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yu55n5bfh"/><circle class="cpk0fnbgt"/><path class="stzdo0biv"/><path class="gwy6q_usg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wiseradar" /></template>
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

.gwy6q_usg {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.57 8.8a18.11 18.11 0 0 1 24.08 5.1");
}

.stzdo0biv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.53 25.4l-10-16.6");
}

.yu55n5bfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.11 38.2l1.42-6.2c-5.69 1.9-10.19.47-14.58-1.54a21.5 21.5 0 0 1 7.23-1.19a40 40 0 0 1-5.93-3.67a23.6 23.6 0 0 0-.59-7.59a41.5 41.5 0 0 1 10.67 4.26a29.6 29.6 0 0 0-1.06-6.64l2.6.72a58 58 0 0 1 2.73-5.46a23.3 23.3 0 0 1 1.9 6.17L30.23 16c-.36 1.9-.6 4-.95 6.17l10.31-3.44c-.35 3.91-.83 7.82-5.21 10.91A28 28 0 0 1 40 30.85C35.8 33 30.46 32.75 24.89 32");
}

</style>

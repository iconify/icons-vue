<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z7baxgjwp"/><circle class="on9wolbfo"/><path class="i3qs_ykdb"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spin-premia" /></template>
<style>
.i3qs_ykdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.317 12.96c-6.048-4.093-14.248-2.98-19.21 2.607");
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

.on9wolbfo {
  cx: 34.315px;
  cy: 14.585px;
  r: 2.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z7baxgjwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.017 35.097c1.345 1.75 3.032 2.403 5.378 2.403h3.247a5.47 5.47 0 0 0 5.471-5.471v-.024a5.47 5.47 0 0 0-5.471-5.471H22.06a5.477 5.477 0 0 1-5.477-5.478a5.49 5.49 0 0 1 5.489-5.489h3.23c2.346 0 4.032.652 5.377 2.403");
}

</style>

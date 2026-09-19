<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="b5sn2ibtp"/><path class="d1g6yubpl"/><path class="qcbylop8j"/><circle class="de3_7eb1v"/><circle class="xw_6xacnv"/><circle class="vm9w11oyb"/><circle class="mt0-v1bat"/><path class="ki7to7zcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rtrnettest" /></template>
<style>
.b5sn2ibtp {
  cx: 24px;
  cy: 24.421px;
  r: 10.848px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d1g6yubpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.682 25.079l3.532-4.888l-4.852 3.568a.91.91 0 0 0-.25.892a1.07 1.07 0 0 0 .678.678a.95.95 0 0 0 .892-.25M9.705 12.648v26.068");
}

.de3_7eb1v {
  cx: 35.773px;
  cy: 38.716px;
  r: 0.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ki7to7zcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.477 27.784h5.046m-4.205 1.682h3.458");
}

.mt0-v1bat {
  cx: 15.591px;
  cy: 6.761px;
  r: 0.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qcbylop8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.718 28.625a8.41 8.41 0 1 1 14.565 0M9.686 38.716h25.246m-3.364-28.591H6.341m-.001 0V32.83m5.869 9.25h26.927M16.432 6.761H42.5m0 0v24.387M39.136 42.08V21.057");
}

.vm9w11oyb {
  cx: 6.341px;
  cy: 33.67px;
  r: 0.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xw_6xacnv {
  cx: 39.136px;
  cy: 20.216px;
  r: 0.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

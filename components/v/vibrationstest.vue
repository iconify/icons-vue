<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xav3-zbdm"/><path class="tda6r_bmc"/><path class="ik38q9tds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vibrationstest" /></template>
<style>
.ik38q9tds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.63 13.63a16.15 16.15 0 0 0 0 20.74m24.74 0a16.15 16.15 0 0 0 0-20.74");
}

.tda6r_bmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.17 38.17a21.5 21.5 0 0 0 0-28.37m-32.34.03a21.5 21.5 0 0 0 0 28.34M15.3 17.3a11 11 0 0 0 0 13.4m17.4 0a11 11 0 0 0 0-13.4");
}

.xav3-zbdm {
  cx: 24px;
  cy: 24px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

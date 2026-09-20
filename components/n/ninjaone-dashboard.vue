<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ivvd4_ymj"/><rect class="pgul6qbwh"/><circle class="xw-ge7htw"/><path class="lpoewzquv"/><circle class="j0090h-9h"/><path class="l0qfpq9me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ninjaone-dashboard" /></template>
<style>
.ivvd4_ymj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.878 34.944v-3.585a2.172 2.172 0 0 0-4.345 0m.001 3.585v-5.757m10.956 4.66a2.172 2.172 0 0 1-4.06-1.076V31.36a2.172 2.172 0 0 1 4.345 0v.706h-4.346");
}

.j0090h-9h {
  cx: 28.868px;
  cy: 13.871px;
  r: 0.75px;
  fill: currentColor;
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

.l0qfpq9me {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 20.063a2.172 2.172 0 0 1-4.345 0V18.65a2.172 2.172 0 0 1 4.345 0m0 3.585v-5.757m-18.655 5.757V18.65a2.172 2.172 0 0 0-4.345 0m0 3.585v-5.757m13.764 5.757V18.65a2.172 2.172 0 0 0-4.345 0m0 3.585v-5.757m6.949 0v7.3c0 .77-.609 1.39-1.369 1.39c-.38 0-.728-.152-.978-.413");
}

.lpoewzquv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.382 16.478v5.757");
}

.pgul6qbwh {
  width: 5.757px;
  height: 8.69px;
  x: 14.226px;
  y: 26.254px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.878px;
  ry: 2.878px;
}

.xw-ge7htw {
  cx: 19.382px;
  cy: 13.817px;
  r: 0.696px;
  fill: currentColor;
}

</style>

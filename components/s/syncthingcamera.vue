<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g7sz5-i2c"/><circle class="s_2_0fbqq"/><path class="v3_udgd1x"/><path class="s1u7y-l3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:syncthingcamera" /></template>
<style>
.g7sz5-i2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.85 19.582a9 9 0 0 0-15.815 5.785m16.495 5.075a8.96 8.96 0 0 0 1.505-4.983a9 9 0 0 0-.146-1.622m-16.662 6.101a9.01 9.01 0 0 0 11.73 3.624");
}

.s_2_0fbqq {
  cx: 25.331px;
  cy: 26.226px;
  r: 2.389px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s1u7y-l3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.832 8.775l-2.768 2.832s-7.409.003-10.774.002A1.79 1.79 0 0 0 4.5 13.4v23.223a1.79 1.79 0 0 0 1.79 1.791h35.418a1.79 1.79 0 0 0 1.791-1.793V13.4a1.79 1.79 0 0 0-1.79-1.793H30.935L28.17 8.775Z");
}

.v3_udgd1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.53 19.484a2.389 2.389 0 1 1 0 4.777q-.104 0-.207-.008a2.388 2.388 0 0 1 .207-4.769m-2.045 9.854a2.383 2.383 0 1 1-.666.094a2.4 2.4 0 0 1 .666-.094m-13.489-4.172a2.389 2.389 0 0 1 .244 4.765a2 2 0 0 1-.244.012a2.389 2.389 0 1 1 0-4.777m2.378 2.168l4.585-.831m4.186-1.831l2.529-1.298m-2.823 4.695l1.324 1.662");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ze9cf4ens"/><path class="tfm-0pbes"/><circle class="m7d1gxybr"/><path class="h21aeeu7q"/><circle class="xf8bxswpv"/><g class="y9tr6bcfx"><path class="spkdcpcwb"/><path class="cf_5k0m7v"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:optimum-support" /></template>
<style>
.cf_5k0m7v {
  d: path("M25.472 38.519a1.472 1.472 0 0 0-2.944 0z");
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

.h21aeeu7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.039 14.637v5.871m-.887-4.477h3.279v4.477m-7.678-1.69a1.69 1.69 0 1 0 3.379 0V17.72a1.69 1.69 0 1 0-3.379 0m0-1.689v6.757");
}

.m7d1gxybr {
  cx: 18.431px;
  cy: 13.962px;
  r: 0.75px;
  fill: currentColor;
}

.spkdcpcwb {
  d: path("M30.813 32.294a6.813 6.813 0 1 0-13.626 0m0 0a2.103 2.103 0 0 0 0 4.206zM30.813 36.5a2.103 2.103 0 0 0 0-4.206zm0 0za2.02 2.02 0 0 1-2.019 2.019h-3.322");
}

.tfm-0pbes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.378 16.031v2.787a1.69 1.69 0 1 0 3.379 0v-2.787m-.001 2.787v1.69M20.057 17.72a1.69 1.69 0 0 1 3.379 0v2.788m-3.379-4.477v4.477m3.379-2.788a1.69 1.69 0 0 1 3.379 0v2.788m6.599-2.788a1.69 1.69 0 0 1 3.379 0v2.788m-3.379-4.477v4.477m3.379-2.788a1.69 1.69 0 0 1 3.379 0v2.788");
}

.xf8bxswpv {
  cx: 42.06px;
  cy: 20.256px;
  r: 0.75px;
  fill: currentColor;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ze9cf4ens {
  width: 3.379px;
  height: 4.477px;
  x: 5.888px;
  y: 16.031px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.689px;
  ry: 1.689px;
}

</style>

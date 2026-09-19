<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8obbsbox"/><circle class="bv9ubsbmk"/><path class="qhje3ccxx"/><circle class="hrmmy9bzn"/><circle class="p_ks3x7dd"/><path class="ue8p9-bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mediatekcamera" /></template>
<style>
.a8obbsbox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.9 40a1.54 1.54 0 0 1-1.4-1.1V11.82A2.23 2.23 0 0 1 6.81 10h34.48a2.06 2.06 0 0 1 2.21 1.41V39c-.1.4-.1.9-.9 1.1Z");
}

.bv9ubsbmk {
  cx: 38.79px;
  cy: 15.13px;
  r: 2.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hrmmy9bzn {
  cx: 23.95px;
  cy: 25.25px;
  r: 12.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p_ks3x7dd {
  cx: 23.95px;
  cy: 25.25px;
  r: 5.31px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qhje3ccxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.41 7.38h4.51v2.54H7.41z");
}

.ue8p9-bls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.65 22.15a3.24 3.24 0 0 0-2.71 2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a3vas2bkx"/><rect class="o1ki421jj"/><path class="mtj__jbik"/><circle class="yp4opcc_d"/><path class="cf_3zjbvq"/><circle class="tbc0nnmcw"/><path class="pm4ik0bog"/><rect class="bel_kac7o"/><path class="byar-d__o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yu-gi-oh-neuron" /></template>
<style>
.a3vas2bkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.255 31.689v-6.287h2.058c1.163 0 2.107.945 2.107 2.111s-.944 2.112-2.107 2.112h-2.058m2.058 0l2.058 2.062m-20.341.002v-6.287l4.165 6.287v-6.287m23.63 6.287v-6.287l4.165 6.287v-6.287m-21.525 0v4.204a2.082 2.082 0 1 0 4.165 0v-4.204m-8.827 3.143h2.05m1.094 3.144h-3.144v-6.287h3.144");
}

.bel_kac7o {
  width: 3.914px;
  height: 5.908px;
  x: 30.607px;
  y: 13.592px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.957px;
  ry: 1.957px;
}

.byar-d__o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.354 15.55a1.957 1.957 0 1 0-3.914 0v1.993a1.957 1.957 0 0 0 3.914 0h-1.957m19.22 17.393H7.383L3.5 28.545l3.883-6.391h33.234l3.883 6.391z");
}

.cf_3zjbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.864 15.586V19.5");
}

.mtj__jbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.731 15.586v2.437a1.477 1.477 0 0 0 2.954 0v-2.437m0 2.437V19.5m22.35-5.908V19.5m0-2.437a1.477 1.477 0 0 1 2.954 0V19.5m-28.651-5.908l-1.957 2.954l-1.957-2.954M8.381 19.5v-2.954");
}

.o1ki421jj {
  width: 4.165px;
  height: 6.287px;
  x: 29.991px;
  y: 25.402px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.083px;
  ry: 2.083px;
}

.pm4ik0bog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.765 13.592v4.394m-25.632-.443h2.954m8.144 0h2.954");
}

.tbc0nnmcw {
  cx: 40.765px;
  cy: 19.5px;
  r: 0.75px;
  fill: currentColor;
}

.yp4opcc_d {
  cx: 24.864px;
  cy: 13.777px;
  r: 0.713px;
  fill: currentColor;
}

</style>

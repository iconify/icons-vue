<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="pfz1h0bwn"/><circle class="ktcbzu_eq"/><path class="qe3cxxbwn"/><path class="gvohhp12a"/><path class="coqu-7b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quo-card-pay" /></template>
<style>
.coqu-7b9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.142 28.388v3.552a2.15 2.15 0 0 1-2.148 2.153a2.15 2.15 0 0 1-2.148-2.153v-3.552m-2 3.553a2.15 2.15 0 0 1-2.148 2.153a2.15 2.15 0 0 1-2.148-2.153v-1.4a2.15 2.15 0 0 1 2.148-2.152a2.15 2.15 0 0 1 2.148 2.153m0 3.552v-5.706");
}

.gvohhp12a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.857 21.596c-2.383 2-5.9 1.846-8.382-.846s-3.904-3-5.172-2.54a3.5 3.5 0 0 0-2.083 2.068m2.638 13.816v-8.612h2.813a2.886 2.886 0 0 1 2.879 2.892a2.886 2.886 0 0 1-2.88 2.893h-2.812m18.284.674v2.907A2.15 2.15 0 0 1 30.994 37c-.593 0-1.13-.24-1.519-.63");
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

.ktcbzu_eq {
  cx: 33.5px;
  cy: 17px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pfz1h0bwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.847 19.191a4 4 0 0 1-4.796 1.537a4 4 0 0 1-2.456-4.594a4 4 0 0 1 4.167-3.125a4 4 0 0 1 3.723 3.642");
}

.qe3cxxbwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21 13v4a3 3 0 1 0 6 0v-4");
}

</style>

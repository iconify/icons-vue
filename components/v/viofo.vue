<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="mfh4xmb3t"/><path class="cys0aeb_k"/><circle class="izq_b7bci"/><path class="avvxcvpsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:viofo" /></template>
<style>
.avvxcvpsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.495 29.987l1.551-1.68M9.101 33.66l1.453-1.573M5.5 37.558l1.567-1.696m28.438-5.875l-1.551-1.68m4.945 5.353l-1.453-1.573m5.054 5.471l-1.567-1.696");
}

.cys0aeb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.742 17.71v-2.744a2.705 2.705 0 0 0-2.697-2.697h-8.09a2.705 2.705 0 0 0-2.697 2.697v2.743a10.3 10.3 0 0 0-3.591 7.82c0 5.707 4.626 10.333 10.333 10.333s10.333-4.626 10.333-10.333a10.3 10.3 0 0 0-3.591-7.82");
}

.izq_b7bci {
  cx: 24px;
  cy: 25.529px;
  r: 2.606px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.mfh4xmb3t {
  cx: 24px;
  cy: 25.529px;
  r: 6.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

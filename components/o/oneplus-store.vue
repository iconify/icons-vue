<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-spa4b1i"/><path class="ap1dv9tby"/><path class="i9clfwm2k"/><path class="dbrdfab8z"/><circle class="dbbi57b2v"/><circle class="t60knubks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oneplus-store" /></template>
<style>
.ap1dv9tby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.505 25.587a2.515 2.515 0 0 1-2.515 2.515h0");
}

.dbbi57b2v {
  cx: 14.944px;
  cy: 10.338px;
  r: 1.525px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dbrdfab8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.944 10.338c0 2.719 4.054 4.923 9.056 4.923s9.057-2.204 9.057-4.923");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.p-spa4b1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.733 25.587v-8.165m-4.398 3.766H36.5m-3.767 7.126v10.108H15.5V21.188h10.108m-1.103 13.09v-8.691");
}

.t60knubks {
  cx: 33.056px;
  cy: 10.338px;
  r: 1.525px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ly81sk3mu"/><circle class="fmxj7iuar"/><path class="q--7s-kgy"/><circle class="hj7n2kbgg"/><path class="qt_5pxbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:viki" /></template>
<style>
.fmxj7iuar {
  cx: 21.692px;
  cy: 17.012px;
  r: 0.75px;
  fill: currentColor;
}

.hj7n2kbgg {
  cx: 35.311px;
  cy: 17.012px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ly81sk3mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.294 21.174l-3.397 9.003l-3.397-9.003m13.826-4.586v13.589m.002-2.887l6.151-6.121m-4.194 4.173l4.836 4.814");
}

.q--7s-kgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.692 21.174v9.003");
}

.qt_5pxbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.311 21.174v9.003");
}

</style>

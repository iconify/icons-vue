<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzq_7zbob"/><rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><path class="n_w3a475m"/><path class="mp09sdefb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:termux-styling" /></template>
<style>
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

.mp09sdefb {
  d: path("M30.155 16.187c-.15-.05-.552-.05-.703 0c-.553.1-1.005.452-1.407.854c-.301.352-.502.754-.703 1.206c-.201.603-.503 1.105-1.055 1.457c-.352.15-.603.351-.905.552l.453.302c.954.452 2.01.603 3.014.301c1.357-.352 2.361-1.909 2.663-3.316");
}

.mzq_7zbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.5 25.327l10.127 5.853L10.5 37.032m22 0H21.673");
}

.n_w3a475m {
  d: path("M31.562 17.594c.15 0 .301-.101.452-.202c.603-.351 1.105-.854 1.558-1.356c2.11-2.11 3.969-4.471 5.727-6.883c.05-.1.15-.251.201-.352c0-.05 0-.2-.05-.25c-.05-.051-.15-.051-.251-.051c-.05 0-.151.1-.251.15c-.704.503-1.457 1.005-2.16 1.508c-1.81 1.306-3.618 2.663-5.226 4.22c-.452.452-.854.955-1.256 1.407c-.15.15-.2.351-.05.552c.251.402.603.804 1.005 1.106c.1.1.15.1.301.15Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

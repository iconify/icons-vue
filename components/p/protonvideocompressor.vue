<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5qahabbw"/><path class="a3h3n0zaz"/><circle class="uav7vbjzt"/><circle class="f9x90jbws"/><circle class="reg3b3b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:protonvideocompressor" /></template>
<style>
.a3h3n0zaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.056 20.585l-11.727 6.77a1.317 1.317 0 0 1-1.976-1.14V12.673a1.317 1.317 0 0 1 1.976-1.141l11.727 6.77a1.317 1.317 0 0 1 0 2.282Z");
}

.f9x90jbws {
  cx: 32.623px;
  cy: 31.558px;
  r: 2.636px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.reg3b3b7h {
  cx: 11.18px;
  cy: 19.444px;
  r: 2.636px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uav7vbjzt {
  cx: 32.291px;
  cy: 7.137px;
  r: 2.636px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y5qahabbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.468 16.592A14.15 14.15 0 0 1 24.182 5.35a17 17 0 0 1 2.28 0a14 14 0 0 1 3.077.594m5.07 2.837a14.1 14.1 0 0 1 4.809 9.525a17 17 0 0 1 0 2.28a14.1 14.1 0 0 1-4.378 9.132m-4.947 3.043a14 14 0 0 1-3.631.78a17 17 0 0 1-2.28 0q-.497-.04-.985-.113c-.623-.094-1.612-.384-2.24-.422a1.91 1.91 0 0 0-2.083 1.107a6.7 6.7 0 0 0-.213 2.252v5.996a1.14 1.14 0 0 1-1.141 1.14h-5.198a1.14 1.14 0 0 1-1.141-1.14V22.128");
}

</style>

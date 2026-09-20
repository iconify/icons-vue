<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="re5gdbvwm"/><path class="p6fpzj2tt"/><circle class="i7wdi9_uf"/><path class="comqsy8-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:square-enix-software-token" /></template>
<style>
.comqsy8-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16a4 4 0 0 0-4 4a4 4 0 0 0 2.12 3.52L20 32h8l-2.12-8.48A4 4 0 0 0 28 20a4 4 0 0 0-4-4M5.5 24H8m34.5 0H40");
}

.i7wdi9_uf {
  cx: 24px;
  cy: 24px;
  r: 12px;
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

.p6fpzj2tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.001 10.144A14 14 0 0 1 26 37.856m-4 0a14 14 0 0 1 0-27.712");
}

.re5gdbvwm {
  cx: 24px;
  cy: 24px;
  r: 16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

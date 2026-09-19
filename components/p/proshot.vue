<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="a2pg8xb9t"/><ellipse class="ox7xn-bqb"/><circle class="mctnzfbhv"/><circle class="w7slz3x4a"/><circle class="ka1-kpbiy"/><circle class="fp1oz5b0x"/><circle class="ltg_zlo9d"/><circle class="gkjkv5bso"/><circle class="jhmc-kbqe"/><path class="w-6ma4jsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proshot" /></template>
<style>
.a2pg8xb9t {
  cx: 7.561px;
  cy: 8.176px;
  r: 1.439px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fp1oz5b0x {
  cx: 33.044px;
  cy: 41.601px;
  r: 0.75px;
  fill: currentColor;
}

.gkjkv5bso {
  cx: 26.969px;
  cy: 43.319px;
  r: 0.75px;
  fill: currentColor;
}

.jhmc-kbqe {
  cx: 39.915px;
  cy: 36.647px;
  r: 0.75px;
  fill: currentColor;
}

.ka1-kpbiy {
  cx: 35.682px;
  cy: 40.257px;
  r: 0.75px;
  fill: currentColor;
}

.ltg_zlo9d {
  cx: 30.206px;
  cy: 42.647px;
  r: 0.75px;
  fill: currentColor;
}

.mctnzfbhv {
  cx: 41.682px;
  cy: 34.531px;
  r: 0.75px;
  fill: currentColor;
}

.ox7xn-bqb {
  cx: 24.231px;
  cy: 21.835px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 17.511px;
  ry: 17.335px;
}

.w-6ma4jsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.631 15.061v13.547m5.733-13.547v13.547m5.733-13.547v13.547m5.733-13.547v13.547");
}

.w7slz3x4a {
  cx: 37.948px;
  cy: 38.589px;
  r: 0.75px;
  fill: currentColor;
}

</style>

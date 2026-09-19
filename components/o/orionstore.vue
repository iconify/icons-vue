<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(5 24 24)" class="mj1-febrd"/><rect transform="rotate(5 28.538 30.591)" class="j3a8z_u9d"/><circle class="kyihs2erv"/><path class="hkpftnb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:orionstore" /></template>
<style>
.hkpftnb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.787 24.074l-7.485-11.089l-9.296 9.621z");
}

.j3a8z_u9d {
  width: 9.589px;
  height: 9.589px;
  x: 23.743px;
  y: 25.796px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.918px;
  ry: 1.918px;
}

.kyihs2erv {
  cx: 17.172px;
  cy: 29.597px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mj1-febrd {
  width: 35.481px;
  height: 35.481px;
  x: 6.259px;
  y: 6.259px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.63px;
  ry: 8.63px;
}

</style>

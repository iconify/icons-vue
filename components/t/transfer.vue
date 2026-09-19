<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bsmmo3b0d"/><rect transform="rotate(10 32.592 23.005)" class="b9m9zxb6a"/><path class="yvheyukcb"/><circle class="zd7c_-bvf"/><circle class="uv_fbkbyr"/><circle class="tl-z5nbwx"/><circle class="lj2x0qief"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transfer" /></template>
<style>
.b9m9zxb6a {
  width: 17.46px;
  height: 28.77px;
  x: 23.84px;
  y: 8.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.03px;
}

.bsmmo3b0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.51 18.47L21 8.73a1 1 0 0 0-1.32-.61l-14.5 5.27a1 1 0 0 0-.62 1.31l9.14 25.11a1 1 0 0 0 1.32.61l10.84-4m-13.01 1.06l8.88-3.24m.09-23.17L5.41 17.04");
}

.lj2x0qief {
  cx: 27.02px;
  cy: 24.27px;
  r: 1.54px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tl-z5nbwx {
  cx: 20.19px;
  cy: 24.27px;
  r: 1.54px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uv_fbkbyr {
  cx: 33.25px;
  cy: 24.27px;
  r: 2.05px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yvheyukcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.08 32.23l17.2 3.03m3.77-21.42l-17.19-3.03");
}

.zd7c_-bvf {
  cx: 13.95px;
  cy: 24.27px;
  r: 2.05px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

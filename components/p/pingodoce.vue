<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="h02x-jjrf"/><circle class="sl0u9abrs"/><path class="o5ns3nbvs"/><rect class="uvbqz59xm"/><path class="c-1xu-bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pingodoce" /></template>
<style>
.c-1xu-bsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.317 17.114a2.205 2.205 0 0 1 4.409 0v1.433a2.205 2.205 0 0 1-4.41 0zM18.619 29.112a2.142 2.142 0 1 1 4.284 0v1.393a2.142 2.142 0 1 1-4.284 0zm-2.013.042a2.14 2.14 0 0 0-2.138-2.139h0a2.14 2.14 0 0 0-2.139 2.139v1.39a2.14 2.14 0 0 0 2.139 2.138h0a2.14 2.14 0 0 0 2.138-2.138m0 2.138v-8.554m12.027 7.417a2.08 2.08 0 0 1-1.81 1.05h0a2.085 2.085 0 0 1-2.085-2.085v-1.355c0-1.151.933-2.084 2.084-2.084h0c.774 0 1.449.42 1.809 1.046m5.839 3.44a2.15 2.15 0 0 1-1.873 1.088h0a2.155 2.155 0 0 1-2.155-2.156v-1.4c0-1.19.965-2.156 2.155-2.156h0c1.19 0 2.155.965 2.155 2.156v.7h-4.31");
}

.h02x-jjrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.076 18.417a2.17 2.17 0 0 0 2.17 2.17h0a2.17 2.17 0 0 0 2.17-2.17v-1.411a2.17 2.17 0 0 0-2.17-2.17h0a2.17 2.17 0 0 0-2.17 2.17m0-2.17v8.681");
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

.o5ns3nbvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.672 14.977v5.778m6.906.058v-3.658a2.217 2.217 0 0 0-2.217-2.218h0a2.217 2.217 0 0 0-2.218 2.218m0 3.658v-5.876m11.045-.086v6.51a2.17 2.17 0 0 1-2.17 2.171h0c-.6 0-1.142-.243-1.535-.636");
}

.sl0u9abrs {
  cx: 17.672px;
  cy: 12.307px;
  r: 0.75px;
  fill: currentColor;
}

.uvbqz59xm {
  width: 4.34px;
  height: 5.751px;
  x: 26.848px;
  y: 14.851px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.17px;
  ry: 2.17px;
}

</style>

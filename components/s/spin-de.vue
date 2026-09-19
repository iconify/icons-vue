<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="oo58at2sa"/><path class="evba41rvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spin-de" /></template>
<style>
.evba41rvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.327 19.73v8.346m-18.134-.704c.567.483 1.18.704 2.556.704h.697c1.134 0 2.054-.934 2.054-2.086s-.92-2.087-2.054-2.087H12.05c-1.134 0-2.054-.934-2.054-2.086s.92-2.087 2.054-2.087h.698c1.375 0 1.988.221 2.555.704m22.7 7.642V22.88c0-1.74-1.391-3.15-3.107-3.15s-3.107 1.41-3.107 3.15m-.001 5.196V19.73m-13.137 5.197c0 1.74 1.391 3.15 3.107 3.15s3.107-1.41 3.107-3.15V22.88c0-1.74-1.39-3.15-3.107-3.15s-3.107 1.41-3.107 3.15m0-3.15v12.598");
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

.oo58at2sa {
  cx: 28.327px;
  cy: 15.872px;
  r: 0.75px;
  fill: currentColor;
}

</style>

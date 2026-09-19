<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i-c-7ccqc"/><g class="y9tr6bcfx"><ellipse class="g5h9ahbbp"/><ellipse class="ok1v784mc"/><path class="l5-3hto5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stickerly" /></template>
<style>
.g5h9ahbbp {
  cx: 17.402px;
  cy: 18.3px;
  rx: 3.046px;
  ry: 4.3px;
}

.i-c-7ccqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.83 45.268C10.023 43.67 1.835 34.032 2.543 22.628c.664-10.707 9.378-19.42 20.085-20.085c11.404-.708 21.043 7.48 22.64 18.287a6 6 0 0 1-1.704 5.106L25.936 43.564a6 6 0 0 1-5.106 1.704");
}

.l5-3hto5a {
  d: path("M33.644 27.835C32.184 32.454 27.982 34 24.39 34s-7.256-1.322-9.255-6.165");
}

.ok1v784mc {
  cx: 30.598px;
  cy: 18.3px;
  rx: 3.046px;
  ry: 4.3px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

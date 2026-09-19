<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="thycqtrxa"/><circle class="z-d61_b6x"/><path class="i4gi94yil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pln-mobile" /></template>
<style>
.i4gi94yil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.457 27.177v5.3m-6.044-3.3a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0m0 2v-8m8.089 0v7a1 1 0 0 0 1 1h.3m5.213-1.01a2 2 0 0 1-1.738 1.009h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v.65h-4M34.856 5.5l-5.144 8.883l6.911-1.852l-5.286 8.675");
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

.thycqtrxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.714 15.521v6.529h3.311m-9.298 0v-6.53h2.168c1.226 0 2.22.982 2.22 2.194s-.994 2.192-2.22 2.192H8.727M19.64 22.05v-6.529l4.387 6.529v-6.529m-3.458 11.656a2 2 0 0 1 2 2v1.3a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2m-11.845 2a2 2 0 1 1 4 0v3.3m-4.001-5.3v5.3m4.001-3.3a2 2 0 1 1 4 0v3.3");
}

.z-d61_b6x {
  cx: 30.457px;
  cy: 24.727px;
  r: 0.75px;
  fill: currentColor;
}

</style>

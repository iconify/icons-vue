<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swb5-j5zj"/><ellipse class="foy8d0brl"/><ellipse class="a5ls8qbmm"/><rect class="au83ontqg"/><rect class="uavth4vbk"/><path class="id9wqq5lm"/><circle class="sceabmbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vendetta-manager" /></template>
<style>
.a5ls8qbmm {
  cx: 28.987px;
  cy: 25.492px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.893px;
  ry: 1.977px;
}

.au83ontqg {
  width: 17.399px;
  height: 37px;
  x: 5.414px;
  y: 5.521px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.foy8d0brl {
  cx: 19.013px;
  cy: 25.492px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.893px;
  ry: 1.977px;
}

.id9wqq5lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.761 8.103h5");
}

.sceabmbiw {
  cx: 14.113px;
  cy: 8.103px;
  r: 0.75px;
  fill: currentColor;
}

.swb5-j5zj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.015 14.527q1.232.05 2.455.216l.79-1.827a13 13 0 0 1 7.417 2.775a35.44 35.44 0 0 1 3.787 15.417s-2.214 3.787-8.049 3.953a38 38 0 0 1-2.26-3.012m-10.176-.013a39 39 0 0 1-2.3 3.025c-5.835-.166-8.049-3.953-8.049-3.953a35.44 35.44 0 0 1 3.803-15.432a13 13 0 0 1 7.416-2.752l.79 1.827q1.084-.15 2.173-.21m0 18.246c-3.595-.263-6.247-1.647-8.98-3.031m20.43 0c-2.8 1.418-5.516 2.836-9.247 3.048");
}

.uavth4vbk {
  width: 17.399px;
  height: 37px;
  x: 25.015px;
  y: 5.521px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>

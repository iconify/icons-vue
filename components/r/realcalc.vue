<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="uzq90320u"/><rect class="r3wf6kbtj"/><rect class="brvmm4_3w"/><path class="bv0hvsbem"/><circle class="z7af6_brl"/><circle class="t--kbeb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:realcalc" /></template>
<style>
.brvmm4_3w {
  width: 16.553px;
  height: 16.553px;
  x: 5.5px;
  y: 25.947px;
  rx: 4px;
  ry: 4px;
}

.bv0hvsbem {
  d: path("M13.776 28.798v10.71m-5.355-5.355h10.711m-1.707-23.957l-7.656 7.49m.083-7.573l7.49 7.656m11.526-3.748h10.711M28.696 34.05h10.711");
}

.r3wf6kbtj {
  width: 16.553px;
  height: 16.553px;
  x: 25.947px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

.t--kbeb1y {
  cx: 34.208px;
  cy: 17.349px;
  r: 1.074px;
}

.uzq90320u {
  d: path("M9.5 5.5a4 4 0 0 0-4 4v8.553a4 4 0 0 0 4 4h8.553a4 4 0 0 0 4-4V9.5a4 4 0 0 0-4-4zm20.447 20.447a4 4 0 0 0-4 4V38.5a4 4 0 0 0 4 4H38.5a4 4 0 0 0 4-4v-8.553a4 4 0 0 0-4-4z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z7af6_brl {
  cx: 34.109px;
  cy: 10.883px;
  r: 1.074px;
}

</style>

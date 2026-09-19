<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="brxpxfbzn"/><path class="j9ees_bxm"/><rect class="nt0_xtbee"/><path class="vbuzx9blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:word-tracer" /></template>
<style>
.brxpxfbzn {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

.j9ees_bxm {
  d: path("M29.796 37.53V27.227h2.319a4.51 4.51 0 0 1 4.508 4.509v1.288a4.51 4.51 0 0 1-4.508 4.508zm-14.152-3.382l3.373 3.38m-6.747.003V27.226h3.374c1.907 0 3.453 1.55 3.453 3.461s-1.546 3.46-3.453 3.46H12.27");
}

.nt0_xtbee {
  width: 6.827px;
  height: 10.305px;
  x: 29.096px;
  y: 10.482px;
  rx: 3.413px;
  ry: 3.413px;
}

.vbuzx9blb {
  d: path("M20.136 10.482L17.56 20.786l-2.576-10.304l-2.576 10.304l-2.577-10.304");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

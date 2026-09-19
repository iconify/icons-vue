<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_gx12b6o"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ostrovok" /></template>
<style>
.j_gx12b6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.28 14.248v13.03m1.716 4.75a1.72 1.72 0 0 1-1.716 1.724h0a1.72 1.72 0 0 1-1.723-1.717v-.007c0-.95.77-1.72 1.72-1.72A1.72 1.72 0 0 1 37 32.025v.003zm-6.733-7.979a9.63 9.63 0 0 1-9.63 9.63A9.63 9.63 0 0 1 11 24.053v-.004a9.63 9.63 0 0 1 9.63-9.63h0a9.63 9.63 0 0 1 9.629 9.63z");
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

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="iggklvbpj"/><circle class="d052l0bxx"/><path class="oh6pmp7an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-one-nz" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d052l0bxx {
  cx: 27.145px;
  cy: 27.771px;
  r: 0.75px;
  fill: currentColor;
}

.iggklvbpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.129 21.227h5.068l-5.068 6.714h5.068m-24.205 0v-4.18c0-1.4-1.134-2.534-2.534-2.534h0a2.534 2.534 0 0 0-2.533 2.534m0 4.18v-6.714m22.118 6.714v-4.18c0-1.4-1.134-2.534-2.534-2.534h0a2.534 2.534 0 0 0-2.533 2.534m0 4.18v-6.714m-5.147 5.435a2.53 2.53 0 0 1-2.202 1.279h0a2.534 2.534 0 0 1-2.533-2.534v-1.646c0-1.4 1.134-2.534 2.533-2.534h0c1.4 0 2.534 1.134 2.534 2.534v.823h-5.067");
}

.oh6pmp7an {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.763 23.76a2.534 2.534 0 1 1 5.068 0v1.647a2.534 2.534 0 1 1-5.068 0z");
}

</style>

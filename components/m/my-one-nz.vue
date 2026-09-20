<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="j42dfnbpg"/><circle class="d052l0bxx"/><path class="oh6pmp7an"/>`;
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

.j42dfnbpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.129 21.227h5.068l-5.068 6.714h5.068m-24.205 0v-4.18a2.534 2.534 0 1 0-5.067 0m0 4.18v-6.714m22.118 6.714v-4.18a2.534 2.534 0 1 0-5.067 0m0 4.18v-6.714m-5.147 5.435a2.534 2.534 0 0 1-4.735-1.255v-1.646a2.534 2.534 0 1 1 5.067 0v.823h-5.067");
}

.oh6pmp7an {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.763 23.76a2.534 2.534 0 1 1 5.068 0v1.647a2.534 2.534 0 1 1-5.068 0z");
}

</style>

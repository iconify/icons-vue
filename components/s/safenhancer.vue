<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t-i8-fy_s"/><path class="verns_bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:safenhancer" /></template>
<style>
.t-i8-fy_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.678 13.044H24.77c-1.963-.108-5.931-4.238-8.188-4.238H6.68v-.001a2.176 2.176 0 0 0-2.18 2.171v7.307h39v-3.418a1.82 1.82 0 0 0-1.822-1.821m1.822 5.239h-39v18.734a2.176 2.176 0 0 0 2.174 2.178h34.645a2.176 2.176 0 0 0 2.181-2.171z");
}

.verns_bsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.546 28.8H27.97v-4.031h-4.03v-1.576a1.454 1.454 0 0 0-2.909 0v1.576H17V28.8h1.576a1.454 1.454 0 1 1 0 2.908H17v4.031h4.031v-1.576a1.454 1.454 0 0 1 2.908 0v1.576h4.031v-4.031h1.576a1.454 1.454 0 1 0 0-2.908");
}

</style>

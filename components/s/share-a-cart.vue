<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="m63es2yjm"/><path class="z275it1bd"/><circle class="fwc7d6bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:share-a-cart" /></template>
<style>
.fwc7d6bpm {
  cx: 19.523px;
  cy: 38.1px;
  r: 3.204px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m63es2yjm {
  cx: 39.296px;
  cy: 38.1px;
  r: 3.204px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z275it1bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 12.875h10.819v16.812H42.5v-7.322m0-15.67L26.855 22.277M42.5 13.638V6.695h-6.942");
}

</style>

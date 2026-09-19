<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><ellipse class="g7c03yz0u"/><path class="lq9k69qon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:you-com" /></template>
<style>
.g7c03yz0u {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.548px;
  ry: 4.518px;
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

.lq9k69qon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.409 19.482V24c0 2.495-2.036 4.517-4.548 4.517S30.313 26.495 30.313 24v-4.518m-12.626 0c0 2.495-2.036 4.518-4.548 4.518S8.59 21.977 8.59 19.482h0M13.139 24v4.518");
}

</style>

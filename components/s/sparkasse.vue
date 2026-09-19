<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="rgb0vo3mk"/><path class="oy5o4pmmm"/><circle class="q35kb7b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sparkasse" /></template>
<style>
.oy5o4pmmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.97 26.14h23.08m-30.1 8.68h23.08");
}

.q35kb7b7x {
  cx: 23.98px;
  cy: 9.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rgb0vo3mk {
  width: 30.1px;
  height: 26.04px;
  x: 8.95px;
  y: 17.46px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
}

</style>

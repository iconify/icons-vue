<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="b_lsnj6mx"/><circle class="o2x8n0b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoop-wallet" /></template>
<style>
.b_lsnj6mx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 25.502h12.555M4.5 14.167h21.932M4.5 19.835h16.866M37.351 8.5C17.74 13.755 21.428 31.169 4.5 31.169m25.109-2.108l1.67 1.67c.838.797 1.854.811 2.75 0l3.299-3.3");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.o2x8n0b3p {
  cx: 33.914px;
  cy: 30.362px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

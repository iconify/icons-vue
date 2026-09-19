<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ver1_9bft"/><path class="vtebcbcyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mizuho-wallet" /></template>
<style>
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

.ver1_9bft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.5c0-3.324 2.676-6 6-6h25c3.324 0 6 2.676 6 6");
}

.vtebcbcyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 20.5c0-3.324 2.676-6 6-6h25c3.324 0 6 2.676 6 6M18.417 32.477V21.323L24 32.489l5.583-11.149v11.149M18 35.71c4.704-1.358 10.645-.967 14.485.954");
}

</style>

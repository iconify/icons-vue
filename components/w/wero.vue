<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s54k3kb4g"/><circle class="w9pt58isi"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wero" /></template>
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

.s54k3kb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.164 21.654A3.318 3.318 0 0 1 23.828 24h-6.636a3.318 3.318 0 0 0 5.664 2.346m2.853.972v-6.636h2.172c1.228 0 2.224.998 2.224 2.229s-.996 2.228-2.224 2.228H25.71m2.171 0l2.172 2.177m-13.917-6.634l-1.659 6.636l-1.659-6.636l-1.659 6.636L9.5 20.682");
}

.w9pt58isi {
  cx: 35.182px;
  cy: 24px;
  r: 3.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

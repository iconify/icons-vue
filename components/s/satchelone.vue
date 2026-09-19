<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="zocld9z-m"/><path class="qmyg6jb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:satchelone" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.qmyg6jb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.396 28.5v-5.604A3.396 3.396 0 0 0 24 19.5h0a3.396 3.396 0 0 0-3.396 3.396m0 5.604v-9m15.536 7.286a3.4 3.4 0 0 1-2.951 1.714h0a3.396 3.396 0 0 1-3.396-3.396v-2.208a3.396 3.396 0 0 1 3.396-3.396h0a3.396 3.396 0 0 1 3.396 3.396V24h-6.793");
}

.zocld9z-m {
  width: 6.793px;
  height: 9px;
  x: 11.415px;
  y: 19.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.396px;
  ry: 3.396px;
}

</style>

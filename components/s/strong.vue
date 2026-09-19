<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tou0ftluy"/><rect class="yqgtvbctm"/><rect class="g_5s4obhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:strong" /></template>
<style>
.g_5s4obhe {
  width: 8px;
  height: 17px;
  x: 31.5px;
  y: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.tou0ftluy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 24h5m-28 0h15m-28 0h5");
}

.yqgtvbctm {
  width: 8px;
  height: 17px;
  x: 8.5px;
  y: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>

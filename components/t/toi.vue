<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aq-uy8bkf"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toi" /></template>
<style>
.aq-uy8bkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.63 17.733c2.345 0 4.233 1.852 4.233 4.152v4.23c0 2.3-1.888 4.15-4.232 4.15s-4.23-1.85-4.23-4.15v-4.23c0-2.3 1.887-4.151 4.23-4.151zM16.731 30.267V17.733m-4.231 0h8.462m14.538 0v12.534");
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

</style>

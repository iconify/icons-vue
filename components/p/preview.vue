<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yy97t8bnc"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:preview" /></template>
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

.yy97t8bnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 30.2h37m-37-12.4h37M30.2 5.5v37m-12.4-37v37m10-23c-.4 0-.7.3-.7.7s.3.7.7.7s.7-.3.7-.7s-.3-.7-.7-.7M24 21.2c-1.5 0-2.8 1.2-2.8 2.8s1.2 2.8 2.8 2.8c1.5 0 2.8-1.2 2.8-2.8c0-1.5-1.3-2.8-2.8-2.8");
}

</style>

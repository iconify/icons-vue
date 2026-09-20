<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="h-zmakb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simple-opengles-info" /></template>
<style>
.h-zmakb0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.36 20v8h4m13.065-.876c.49.639 1.106.877 1.962.877h1.184a1.996 1.996 0 0 0 1.996-1.996v-.009A1.996 1.996 0 0 0 36.57 24h-1.307a2 2 0 0 1-1.997-1.997c0-1.106.896-2.003 2.002-2.003h1.178c.855 0 1.47.238 1.961.877M27.634 24h2.608m1.388-4h-4v8h4M22 24h4m-11.267-1.35a2.65 2.65 0 1 0-5.3 0v2.7a2.65 2.65 0 1 0 5.3 0h-2.65");
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

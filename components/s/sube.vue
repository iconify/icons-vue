<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ojz-_0b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sube" /></template>
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

.ojz-_0b6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.834 27.124c.49.639 1.106.877 1.962.877h1.184a1.996 1.996 0 0 0 1.996-1.996v-.009A1.996 1.996 0 0 0 12.98 24h-1.306a2 2 0 0 1-1.998-1.997c0-1.106.896-2.003 2.002-2.003h1.178c.856 0 1.47.238 1.961.877M17.892 20v5.35a2.65 2.65 0 1 0 5.3 0V20m11.132 4h2.61m1.39 4h-4v-8h4m-8.916 4a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.296m-2.92-5.5l-2.65-2.65l-2.65 2.65");
}

</style>

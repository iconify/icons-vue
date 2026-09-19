<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vmxf93b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:researchgate" /></template>
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

.vmxf93b4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.36 38.035v-19.2h6.285c3.553 0 6.434 2.887 6.434 6.448s-2.88 6.448-6.434 6.448H11.36m6.287.002l6.288 6.297M36.64 13.781a3.815 3.815 0 1 0-7.63 0v3.887a3.815 3.815 0 1 0 7.63 0h-3.815");
}

</style>

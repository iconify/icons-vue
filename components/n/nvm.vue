<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o00gimb9c"/><path class="hc77isnme"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nvm" /></template>
<style>
.hc77isnme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.755 23.066a2.873 2.873 0 1 1 5.745 0v4.74m-21.255 0v-4.74a2.873 2.873 0 1 0-5.745 0m0 4.74v-7.612");
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

.o00gimb9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.654 20.194l-2.873 7.612l-2.873-7.612m8.102 2.872a2.873 2.873 0 1 1 5.745 0v4.74m-5.746-7.612v7.612");
}

</style>

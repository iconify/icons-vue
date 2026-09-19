<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgyed1ldr"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nvm" /></template>
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

.rgyed1ldr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.654 20.194l-2.873 7.612l-2.873-7.612m8.102 2.872a2.873 2.873 0 0 1 2.872-2.872h0a2.873 2.873 0 0 1 2.873 2.872v4.74m-5.746-7.612v7.612m5.746-4.74a2.873 2.873 0 0 1 2.872-2.872h0a2.873 2.873 0 0 1 2.873 2.872v4.74m-21.255 0v-4.74a2.873 2.873 0 0 0-2.872-2.872h0a2.873 2.873 0 0 0-2.873 2.872m0 4.74v-7.612");
}

</style>

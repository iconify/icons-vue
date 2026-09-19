<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u2excbbcw"/><path class="k4q0al2ah"/><path class="oiqcybw1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notificationlog" /></template>
<style>
.k4q0al2ah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.327 38.827a4.651 4.651 0 1 0 9.301.043v-.043m-6.5-10.527a2.437 2.437 0 0 1-2.43-2.43v-1.58a2.437 2.437 0 0 1 2.43-2.43h0a2.437 2.437 0 0 1 2.43 2.43v1.58a2.437 2.437 0 0 1-2.43 2.43m-6.045-9.72v8.505a1.148 1.148 0 0 0 1.215 1.215h.364m14.255-6.44v7.29a2.437 2.437 0 0 1-2.43 2.43h0a2.04 2.04 0 0 1-1.7-.728");
}

.oiqcybw1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.487 21.86a2.437 2.437 0 0 1 2.43 2.43v1.58a2.437 2.437 0 0 1-2.43 2.43h0a2.437 2.437 0 0 1-2.43-2.43v-1.58a2.437 2.437 0 0 1 2.43-2.43");
}

.u2excbbcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.276 32.68V21.472A13.27 13.27 0 0 0 27.08 8.568v-.985a3.102 3.102 0 0 0-6.203 0v.997a13.27 13.27 0 0 0-10.153 12.89v11.21L6.52 36.886v1.942h34.96v-1.942Z");
}

</style>

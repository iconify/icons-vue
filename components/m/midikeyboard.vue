<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udptpab7m"/><path class="aps1-9bfw"/><path class="sdteiu02v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:midikeyboard" /></template>
<style>
.aps1-9bfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.24 45.45A21.87 21.87 0 0 1 2.71 21.37A21.61 21.61 0 0 1 24.09 2.5a21.63 21.63 0 0 1 21.23 19.06A21.87 21.87 0 0 1 29.58 45.5");
}

.sdteiu02v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.58 45.5l-1-4.18h-9.41l-.93 4.13M14 5v22.8H7.12v-17m20.11-8.04v25.06h-6.84v-25m-9.69 25v13.74m26.19-13.74v14.07M23.84 27.82v13.49");
}

.udptpab7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.67 4.84v23h6.89V10.43");
}

</style>

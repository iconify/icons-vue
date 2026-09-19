<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gwa2aubcp"/><path class="gvu3cknig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sunilpaulmathew-weather" /></template>
<style>
.gvu3cknig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 23.995h7.346M23.997 45.5v-7.35m0-28.3V2.5m14.157 21.495H45.5M8.79 39.192l5.195-5.194M39.2 39.2l-5.198-5.198M13.989 13.991L8.79 8.794m25.212 5.19l5.194-5.194");
}

.gwa2aubcp {
  cx: 23.997px;
  cy: 23.995px;
  r: 9.438px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjistr38k"/><path class="mz5nqpb8g"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:niagara-launcher-recently-installed" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mz5nqpb8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.063 24.19l1.949 1.949l1.948-1.949M24 24v-7.546m3.457 11.003L24 24");
}

.vjistr38k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.23 31.77A10.95 10.95 0 0 0 24 34.988c6.069 0 10.988-4.92 10.988-10.988S30.068 13.012 24 13.012S13.012 17.932 13.012 24v2.139");
}

</style>

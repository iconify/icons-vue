<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z24hk6b0n"/><path class="n24sikbpz"/><circle class="wsiusfbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:offerup" /></template>
<style>
.n24sikbpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.494 28.272l7.997 11.513l23.522-15.73l1.487-9.882");
}

.wsiusfbur {
  cx: 39.339px;
  cy: 14.912px;
  r: 0.75px;
  fill: currentColor;
}

.z24hk6b0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.369 28.832l30.755-5.516l5.376-9.143l-8.245-5.958L4.5 13.73z");
}

</style>

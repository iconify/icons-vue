<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 20.983 27.017)" class="qib4r2bcm"/><circle class="tv30l4bnm"/><path class="twwahp4kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:remote-mouse" /></template>
<style>
.qib4r2bcm {
  width: 21.522px;
  height: 34.878px;
  x: 10.222px;
  y: 9.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.761px;
}

.tv30l4bnm {
  cx: 25.61px;
  cy: 22.39px;
  r: 1.92px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.twwahp4kt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.724 14.577a9.66 9.66 0 0 0-5.257-5.283m9.033 3.678A13.78 13.78 0 0 0 35.028 5.5");
}

</style>

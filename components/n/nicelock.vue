<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="to6pi4ver"/><circle class="oxg094b3b"/><path class="v6rxr3b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nicelock" /></template>
<style>
.oxg094b3b {
  cx: 24px;
  cy: 27px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.to6pi4ver {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.293 18.646l16.5-12.487a2 2 0 0 1 2.414 0l16.5 12.487a2 2 0 0 1 .793 1.595v18.005a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4V20.241a2 2 0 0 1 .793-1.595");
}

.v6rxr3b-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.46 28.386c.61 2.49 2.86 4.33 5.54 4.33s4.93-1.84 5.54-4.33m-9.732-3.716v-.946m8.384.946v-.946");
}

</style>

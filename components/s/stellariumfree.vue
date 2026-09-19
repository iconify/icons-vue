<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="l8aqbxr3j"/><circle class="f3qvb3b9m"/><circle class="pl8efvdru"/><circle class="xxozbprnq"/><circle class="t88xvwbzq"/><path class="dalbmubfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stellariumfree" /></template>
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

.dalbmubfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.2 44.17l-11.32-19.6l-3.58 6.2l-1.66-2.88L12 30.73L5.54 19.57l-2.71 4.69m14-7.26");
}

.f3qvb3b9m {
  cx: 17.01px;
  cy: 11.68px;
  r: 0.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l8aqbxr3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.16 36.79c3.87-2.7 12.57-4.64 17.1-3.56m-8.51-21.91a6.9 6.9 0 0 1-5.37 12.25a6.9 6.9 0 1 0 5.37-12.25M14.52 9.84");
}

.pl8efvdru {
  cx: 14.71px;
  cy: 25.08px;
  r: 0.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t88xvwbzq {
  cx: 10.8px;
  cy: 11.91px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xxozbprnq {
  cx: 21.12px;
  cy: 22.9px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

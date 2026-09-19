<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="be1u8ibnk"/><circle class="h397d3j1k"/><circle class="e60d76bky"/><path class="kgkouo3by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taskito" /></template>
<style>
.be1u8ibnk {
  cx: 9.5px;
  cy: 9.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e60d76bky {
  cx: 9.5px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h397d3j1k {
  cx: 9.5px;
  cy: 38.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kgkouo3by {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 13.5V20m0 8v6.5m9-25h24M18.5 24h24m-24 14.949h24M7.836 10.048l.744.744l2.584-2.584m-3.328 30.84l.744.744l2.584-2.584m-3.328-12.66l.744.744l2.584-2.584");
}

</style>

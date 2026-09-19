<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dmy5m9bzm"/><circle class="jgwsbpb4g"/><path class="af-ff9hvr"/><path class="n3dyxpphz"/><path class="bxc5obbxd"/><path class="rmksew-1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sleeper" /></template>
<style>
.af-ff9hvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.719 35.519l2.801 7.791m.657-12.92c0 1.103-1.146 1.973-2.632 1.973s-4.394-1.655-4.394-3.523c0-.446.276-.833.801-.833c.426 0 3.294 1.252 5.079 1.49c1.03.139 1.146.472 1.146.892");
}

.bxc5obbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.807c11.83 0 13.302 5.66 13.302 8.434v3.849s-7.5 1.98-13.302 1.98s-13.302-1.98-13.302-1.98v-3.85c0-2.773 1.472-8.433 13.302-8.433m6.281 13.712L27.48 43.31");
}

.dmy5m9bzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.934V9.255");
}

.jgwsbpb4g {
  cx: 24px;
  cy: 6.877px;
  r: 2.377px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n3dyxpphz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.934c11.264 0 15.962 8.525 15.962 16.376S36.34 43.5 24 43.5S8.038 37.16 8.038 29.31S12.736 12.934 24 12.934");
}

.rmksew-1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.823 30.39c0 1.103 1.146 1.973 2.632 1.973s4.394-1.655 4.394-3.523c0-.446-.276-.833-.801-.833c-.426 0-3.294 1.252-5.079 1.49c-1.03.139-1.146.472-1.146.892");
}

</style>

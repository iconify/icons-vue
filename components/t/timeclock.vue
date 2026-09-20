<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e0sv3nbiw"/><circle class="velaxob7v"/><path class="tj9hmtb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:timeclock" /></template>
<style>
.e0sv3nbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.434 33.099H14.566m0 10.401h18.868l-2.968-10.401H16.898z");
}

.tj9hmtb6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.677v-7.364m0 7.364l-3.85 1.861M15.27 40.36H13a3.177 3.177 0 0 1-3.177-3.177V7.677A3.177 3.177 0 0 1 12.999 4.5h22.002a3.177 3.177 0 0 1 3.176 3.177v29.506a3.177 3.177 0 0 1-3.176 3.177h-2.463");
}

.velaxob7v {
  cx: 24px;
  cy: 18.677px;
  r: 10.388px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

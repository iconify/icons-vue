<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="g1wvz6v4a"/><path class="e2je4-b2l"/><circle class="ezfyt9btu"/><path class="z8yzy76nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mint" /></template>
<style>
.e2je4-b2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.553 23.168a2.526 2.526 0 1 1 5.053 0v4.169");
}

.ezfyt9btu {
  cx: 24.069px;
  cy: 17.547px;
  r: 0.75px;
  fill: currentColor;
}

.g1wvz6v4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 23.168a2.526 2.526 0 1 1 5.053 0v4.169M11.5 20.642v6.695");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.z8yzy76nz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.069 20.642v6.695m10.789-8.779v7.516c0 .697.565 1.263 1.263 1.263h.379m-2.968-6.695h2.652m-4.147 6.695v-4.168a2.526 2.526 0 1 0-5.053 0m0 4.168v-6.695");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v_yhzm9xu"/><circle class="smh8hwt4g"/><path class="vo5ct2b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nesoid" /></template>
<style>
.smh8hwt4g {
  cx: 24px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v_yhzm9xu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 18H30V7.5a2 2 0 0 0-2-2h-8a2 2 0 0 0-2 2V18H7.5a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2H18v10.5a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V30h10.5a2 2 0 0 0 2-2v-8a2 2 0 0 0-2-2");
}

.vo5ct2b4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.596 24l-4.028-4v1.672h-3.164v4.656h3.164V28zM7.404 24l4.028 4v-1.672h3.163v-4.656h-3.163V20zM24 40.596l4-4.028h-1.672v-3.164h-4.656v3.164H20zm0-33.192l-4 4.028h1.672v3.163h4.656v-3.163H28z");
}

</style>

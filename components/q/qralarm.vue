<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-44.72 9.485 11.406)" class="cnph9o51f"/><rect transform="rotate(-45.28 38.515 11.418)" class="x5g16ul3a"/><circle class="jk1onxpna"/><path class="g6bzqdbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qralarm" /></template>
<style>
.cnph9o51f {
  width: 13.452px;
  height: 4.479px;
  x: 2.76px;
  y: 9.166px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.892px;
  ry: 0.892px;
}

.g6bzqdbnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.55 15.28h-4.414v4.415m19.729 0V15.28H29.45m0 19.729h4.415v-4.415M16.828 26.43v5.865h5.866v-5.866zm0-8.457v5.865h5.866v-5.865zm8.457 0v5.865h5.866v-5.865zm2.944 14.343a3.1 3.1 0 0 0 1.85-1.12a4.46 4.46 0 0 0 1.093-3.05V26.43h-5.865v1.717a4.47 4.47 0 0 0 1.093 3.05c.456.58 1.105.977 1.829 1.12m-14.093-1.723v4.415h4.415");
}

.jk1onxpna {
  cx: 24.099px;
  cy: 25.961px;
  r: 16.588px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x5g16ul3a {
  width: 4.479px;
  height: 13.451px;
  x: 36.275px;
  y: 4.692px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.892px;
  ry: 0.892px;
}

</style>

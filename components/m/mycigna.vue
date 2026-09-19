<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ii3m1acch"/><rect transform="matrix(-1 0 0 -1 43.054 48.538)" class="z5vokcbjc"/><circle class="ceh9clblz"/><path class="qv1-igfyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mycigna" /></template>
<style>
.ceh9clblz {
  cx: 16.55px;
  cy: 18.168px;
  r: 0.75px;
  fill: currentColor;
}

.ii3m1acch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.92 21.099v7.178a2.393 2.393 0 0 1-2.393 2.393h0c-.66 0-1.259-.268-1.692-.701");
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

.qv1-igfyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.55 21.099v6.34m-2.58-1.205a2.39 2.39 0 0 1-2.077 1.205h0A2.393 2.393 0 0 1 9.5 25.048v-1.555a2.393 2.393 0 0 1 2.393-2.393h0c.887 0 1.662.483 2.075 1.2M38.5 25.047a2.393 2.393 0 0 1-2.393 2.393h0a2.393 2.393 0 0 1-2.392-2.393v-1.555a2.393 2.393 0 0 1 2.392-2.393h0a2.393 2.393 0 0 1 2.393 2.393m0 3.947v-6.34m-7.254 6.341v-3.95a2.393 2.393 0 0 0-2.392-2.392h0a2.393 2.393 0 0 0-2.393 2.392m0 3.949v-6.34m-7.368-2.931h1.189m.108-1.546l.626-.252m-2.844-2.01l.265-.621m-3.432.589l-.253-.626m-2.01 2.844l-.621-.264m6.228.088l.84-.84m-2.639.095v-1.188m-1.798 1.933l-.84-.84m.095 2.638h-1.188");
}

.z5vokcbjc {
  width: 4.785px;
  height: 6.341px;
  x: 19.134px;
  y: 21.099px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.393px;
  ry: 2.393px;
}

</style>

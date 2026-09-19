<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yoplx8bpm"/><circle class="z87mw1xts"/><circle class="wf0egjbrh"/><circle class="ket8gu5uw"/><path class="pjx_rtbuo"/><path class="cz5by-v5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:melon-playground" /></template>
<style>
.cz5by-v5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42 24.762c.668 9.347-2.037 17.004-15.979 17.708c-10.448.528-14.064-6.066-15.492-14.505");
}

.ket8gu5uw {
  cx: 36.545px;
  cy: 20.072px;
  r: 3.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pjx_rtbuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.686 34.2L42 24.762m-2.234-3.77c.105 1.84.652 3.278 2.235 3.77M35.35 15.59L10.529 27.965l-4.085-7.893C2.334 8.617 22.822-1.684 32.716 12.129c.806 1.125 3.538-2.892 4.67-.744c.347.744-.18 3.17-2.036 4.205m0 0l1.195 1.132");
}

.wf0egjbrh {
  cx: 36.545px;
  cy: 20.072px;
  r: 1.149px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yoplx8bpm {
  cx: 23.77px;
  cy: 25.784px;
  r: 1.149px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z87mw1xts {
  cx: 23.77px;
  cy: 25.784px;
  r: 3.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

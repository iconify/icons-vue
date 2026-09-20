<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="snrn6ub4c"/><circle class="bcofmaczm"/><circle class="xci3rjb6a"/><circle class="ff9qsyb5f"/><path class="vtpojk0cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:threema" /></template>
<style>
.bcofmaczm {
  cx: 13.63px;
  cy: 40.6px;
  r: 2.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ff9qsyb5f {
  cx: 34.37px;
  cy: 40.6px;
  r: 2.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.snrn6ub4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c-10.08 0-18.26 6.32-18.26 14.11a12.66 12.66 0 0 0 5.06 9.73L7.34 35l10.2-3.21a22.9 22.9 0 0 0 6.46.93c10.08 0 18.26-6.31 18.26-14.1S34.08 4.5 24 4.5m0 4.15a5 5 0 0 1 5 5v4.15h.71a1 1 0 0 1 .95.95V26a1 1 0 0 1-.95.95h-11.4a1 1 0 0 1-.95-.95v-7.27a1 1 0 0 1 .95-.95H19v-4.15a5 5 0 0 1 5-4.98");
}

.vtpojk0cy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.02 17.78h9.96");
}

.xci3rjb6a {
  cx: 24px;
  cy: 40.6px;
  r: 2.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

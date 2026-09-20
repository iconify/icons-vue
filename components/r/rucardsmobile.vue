<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6xlfq7ox"/><path class="oj_zlijdr"/><circle class="mugq-dtat"/><circle class="hm1lmac1k"/><path class="fb4rl4bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rucardsmobile" /></template>
<style>
.fb4rl4bze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.25 30.548l5.463-8.403m-24.2-2.305h34.534M4.513 24.042h5.252m24.043 0h5.252");
}

.hm1lmac1k {
  cx: 28.082px;
  cy: 28.972px;
  r: 1.576px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mugq-dtat {
  cx: 23.881px;
  cy: 23.72px;
  r: 1.576px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oj_zlijdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.94 13.865v-.885a2.1 2.1 0 0 1 2.1-2.1H41.4a2.1 2.1 0 0 1 2.1 2.1v17.28a2.1 2.1 0 0 1-2.1 2.1h-.413m-26.035-1.745v-8.403m-1.05-.067l3.78.067m0 0a2.836 2.836 0 0 1 0 5.672h-3.78m0 1.575h3.781");
}

.w6xlfq7ox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.6 15.639h30.36a2.1 2.1 0 0 1 2.101 2.1V35.02a2.1 2.1 0 0 1-2.1 2.1H6.6a2.1 2.1 0 0 1-2.1-2.1V17.74a2.1 2.1 0 0 1 2.1-2.101");
}

</style>

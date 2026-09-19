<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjm1qhb_m"/><path class="qscbn3byp"/><circle class="yl94lpfnl"/><path class="rf_eeizwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:virginmoney" /></template>
<style>
.qscbn3byp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.348 20.4H43.5v7.2h-7.152a2.85 2.85 0 0 1-2.848-2.848v-1.504a2.85 2.85 0 0 1 2.848-2.848");
}

.rf_eeizwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 27.545s2.11-3.932 2.617-4.468c0 0 2.363 7.506 2.617 10.484c.59-3.336 4.052-17.037 7.766-19.122");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

.yl94lpfnl {
  cx: 36.472px;
  cy: 24px;
  r: 0.795px;
  fill: currentColor;
}

</style>

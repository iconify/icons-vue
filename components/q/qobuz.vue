<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lyvtvlboq"/><circle class="e-kpfd57i"/><path class="dfshu4big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qobuz" /></template>
<style>
.dfshu4big {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.944 32.944L45.5 45.5");
}

.e-kpfd57i {
  cx: 24px;
  cy: 24px;
  r: 4.873px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lyvtvlboq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203A21.43 21.43 0 0 0 45.5 24c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24S12.126 45.5 24 45.5c4.89 0 9.4-1.633 13.012-4.383");
}

</style>

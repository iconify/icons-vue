<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m2xeh0bxx"/><path class="hijb4dbor"/><circle class="mz3va0o8b"/><path class="jsnj27-vl"/><path class="klo9dbc-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nofbeventscraper" /></template>
<style>
.hijb4dbor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.826 19.291h6.324v6.324h-6.324zm9.627 0h6.324v6.324h-6.324zm-19.252 0h6.324v6.324H9.201zm9.625 9.838h6.324v6.324h-6.324zm-9.625 0h6.324v6.324H9.201zM12.43 5.5h2.403a1 1 0 0 1 1 1h0v5.043a1 1 0 0 1-1 1H12.43a1 1 0 0 1-1-1V6.5a1 1 0 0 1 1-1m16.714 0h2.402a1 1 0 0 1 1 1v5.043a1 1 0 0 1-1 1h-2.402a1 1 0 0 1-1-1h0V6.5a1 1 0 0 1 1-1");
}

.jsnj27-vl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.81 39.977l-3.121-2.202l-3.279 1.96l1.13-3.65l-2.878-2.512l3.82-.053l1.5-3.514l1.23 3.617l3.806.34l-3.06 2.29Z");
}

.klo9dbc-d {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 5.571;
  d: path("M6.404 16.24h31.405");
}

.m2xeh0bxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.963 39.837H8.176a2 2 0 0 1-2-2h0V10.212a2 2 0 0 1 2-2h2.955m5.288 0h11.64m4.542 0h3.201a2 2 0 0 1 2 2V28.83");
}

.mz3va0o8b {
  cx: 34.776px;
  cy: 35.452px;
  r: 7.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cdr06z_hk"/><path class="pq2so9fpz"/><path class="tb10s1o2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trafficlight" /></template>
<style>
.cdr06z_hk {
  cx: 28.367px;
  cy: 34.187px;
  r: 9.313px;
  fill: none;
  stroke: currentColor;
}

.pq2so9fpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M14.619 22.558a9.89 9.89 0 0 1-4.3-8.162c0-5.466 4.431-9.896 9.896-9.896s9.896 4.43 9.896 9.896q-.002.862-.143 1.685");
}

.tb10s1o2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M19.096 32.661a9.89 9.89 0 0 1-4.615-8.37c0-5.465 4.43-9.895 9.895-9.895s9.896 4.43 9.896 9.895c0 .815-.099 1.606-.284 2.364");
}

</style>

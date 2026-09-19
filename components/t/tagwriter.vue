<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kv9qrvbwh"/><circle class="cpvtk4bck"/><path class="da0p26h0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tagwriter" /></template>
<style>
.cpvtk4bck {
  cx: 17.17px;
  cy: 12.04px;
  r: 1.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.da0p26h0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28 35.6v5.2H6.21V14.35l10.9-7.15L28 14.35v15.18m-5.27 5.34l3.01 3.01");
}

.kv9qrvbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 18.62L19.81 37.79v3h3L42 21.63l-3-3m-1.85 1.82l3 3M6.21 37A3.81 3.81 0 0 1 10 40.8h0M6.21 27.22A13.58 13.58 0 0 1 19.79 40.8h0M6.21 32.2a8.61 8.61 0 0 1 8.61 8.6");
}

</style>

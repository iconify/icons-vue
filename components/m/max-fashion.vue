<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="gzuhtcc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:max-fashion" /></template>
<style>
.gzuhtcc1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.5 20.933l-4.63 6.134m4.63 0l-4.63-6.134M12.5 23.248a2.315 2.315 0 0 1 4.63 0v3.82m-4.63-6.135v6.134m4.63-3.819a2.315 2.315 0 0 1 4.63 0v3.82m6.73-2.316a2.315 2.315 0 0 1-4.63 0v-1.504a2.315 2.315 0 0 1 4.63 0m0 3.819v-6.134");
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

</style>

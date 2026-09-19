<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e5rma-bat"/><circle class="gdht4sb7j"/><circle class="sfndxs8at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-camera" /></template>
<style>
.e5rma-bat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.284 10.824H8.716A4.216 4.216 0 0 0 4.5 15.04v17.92a4.216 4.216 0 0 0 4.216 4.216h30.568a4.216 4.216 0 0 0 4.216-4.217V15.041a4.216 4.216 0 0 0-4.216-4.217");
}

.gdht4sb7j {
  cx: 24px;
  cy: 24px;
  r: 7.905px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sfndxs8at {
  cx: 37.703px;
  cy: 16.622px;
  r: 2.635px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

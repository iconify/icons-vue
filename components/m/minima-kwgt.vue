<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mn8ksmb4e"/><circle class="vmq5w63tk"/><path class="k8d-ybcye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minima-kwgt" /></template>
<style>
.k8d-ybcye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.214 33.148v8.016m3.692 0v-2.053l-2.073-1.955l2.073-1.955v-2.053");
}

.mn8ksmb4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.94 11.906v21.5m37.24-21.5v19.592M27.215 3.844v37.625M31.87 6.531v25.885m4.655-23.198v20.92M17.905 3.844v37.625M13.25 6.531v32.25M8.595 9.218v26.875m9.31-32.249L22.56 6.53l4.654-2.687m-9.309 4.95l4.655 2.688l4.654-2.688m-9.309 4.949l4.655 2.688l4.654-2.688m-9.309 4.949l4.655 2.688l4.654-2.688");
}

.vmq5w63tk {
  cx: 37.06px;
  cy: 37.156px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

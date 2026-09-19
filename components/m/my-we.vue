<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="e9efwvbnn"/><path class="h5ttbhsdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-we" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e9efwvbnn {
  d: path("M40.02 27.507S40.02 29 36.856 29H28.3s-3.012.025-3.012-3.543v-3.569s-.025-2.885 2.658-2.885h9.896s2.53-.177 2.53 2.202l.026 2.78H25.315M15.175 19v7.7a2.3 2.3 0 0 1-2.3 2.3H9.9a2.3 2.3 0 0 1-2.3-2.3V19");
}

.h5ttbhsdr {
  d: path("M22.75 19v7.7a2.3 2.3 0 0 1-2.3 2.3h-2.975a2.3 2.3 0 0 1-2.3-2.3V19");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

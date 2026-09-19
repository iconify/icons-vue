<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_1c4zbag"/><g class="y9tr6bcfx"><path class="a10mu5gev"/><path class="e78kmhe9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youtubevanced" /></template>
<style>
.a_1c4zbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.112 14.394a5 5 0 0 0-3.533-3.533c-2.314-.894-24.732-1.332-31.236.025A5 5 0 0 0 4.81 14.42c-1.045 4.583-1.124 14.491.026 19.177a5 5 0 0 0 3.533 3.533c4.583 1.055 26.371 1.203 31.236 0a5 5 0 0 0 3.533-3.533c1.114-4.993 1.193-14.287-.026-19.203");
}

.a10mu5gev {
  d: path("m19.472 31.495l10.051-5.765c1.34-.768 1.34-2.701 0-3.47l-10.051-5.765");
}

.e78kmhe9v {
  d: path("M25.103 23.475L20.37 20.76a.6.6 0 0 0-.899.521v5.428a.6.6 0 0 0 .899.52l4.732-2.713a.6.6 0 0 0 0-1.041");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

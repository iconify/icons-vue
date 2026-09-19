<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dfiaby94d"/><path class="xy5ud4bes"/><path class="q24fwpb7l"/><circle class="cpk0fnbgt"/><path class="eh6254sjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mbank-cz" /></template>
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

.dfiaby94d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.22 22.13a6.134 6.134 0 0 1 5.993-6.232a6.134 6.134 0 0 1 5.993 6.232v9.971M13.22 15.898v16.204");
}

.eh6254sjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 6.25;
  d: path("M13.22 5.398v6.479m0 24.723v6.002M25.206 2.746v9.13m.02 24.724l-.02 8.793M37.154 6.994v4.883m0 24.723v4.406");
}

.q24fwpb7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 6.25;
  d: path("M13.22 15.898h-2.403");
}

.xy5ud4bes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.206 22.13a5.998 5.998 0 1 1 11.986 0v9.971");
}

</style>

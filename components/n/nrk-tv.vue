<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ulg-y3b-w"/><path class="mw92e95qe"/><circle class="gwao55b_f"/><path class="nfsju1bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nrk-tv" /></template>
<style>
.gwao55b_f {
  cx: 25.986px;
  cy: 14.243px;
  r: 2.339px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mw92e95qe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 11.903h-4.679l-4.679 6.449l4.679 6.449H42.5l-4.679-6.449zM18.967 24.802H14.29l-4.11-12.899h2.06c1.56 0 2.94 1.01 3.414 2.495z");
}

.nfsju1bma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 28.097h5.3m-2.65 8v-8m9.977 0l-2.651 8l-2.65-8");
}

.ulg-y3b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.903h4.679v12.898H5.5zm13.467 0h4.679v12.898h-4.679zm9.497 0h4.679v12.898h-4.679z");
}

</style>

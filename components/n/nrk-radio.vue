<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ulg-y3b-w"/><path class="mw92e95qe"/><circle class="gwao55b_f"/><path class="olkvdsbqi"/><circle class="wrbzd0bux"/><path class="itfxq71lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nrk-radio" /></template>
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

.itfxq71lv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.668 30.797v5.3m-8.214-2a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3m6.019 2a2 2 0 1 0-4 0v1.3a2 2 0 1 0 4 0m0 2v-8m4.183 4.7a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0z");
}

.mw92e95qe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 11.903h-4.679l-4.679 6.449l4.679 6.449H42.5l-4.679-6.449zM18.967 24.802H14.29l-4.11-12.899h2.06c1.56 0 2.94 1.01 3.414 2.495z");
}

.olkvdsbqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 36.097v-8h2.619c1.48 0 2.681 1.203 2.681 2.687S9.6 33.47 8.119 33.47H5.5m2.619 0l2.619 2.625");
}

.ulg-y3b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.903h4.679v12.898H5.5zm13.467 0h4.679v12.898h-4.679zm9.497 0h4.679v12.898h-4.679z");
}

.wrbzd0bux {
  cx: 24.668px;
  cy: 28.347px;
  r: 0.75px;
  fill: currentColor;
}

</style>

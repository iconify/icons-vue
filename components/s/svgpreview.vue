<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wug-328ss"/><circle class="qniq2hb6i"/><circle class="s4bqr4b1m"/><path class="z9kx-pbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:svgpreview" /></template>
<style>
.qniq2hb6i {
  cx: 13.317px;
  cy: 36.47px;
  r: 4.196px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s4bqr4b1m {
  cx: 34.717px;
  cy: 36.47px;
  r: 4.196px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wug-328ss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 25.873V12.864l2.828-2.828h23.646L42.5 20.563v8.06H8.25zm5.327 7.225v-2.389H37.64v2.754m-6.002 5.852H16.397");
}

.z9kx-pbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.397 28.623v2.086m15.909-2.086v2.086m-5.358-20.673l-.655-2.702h-1.62l-.656 2.702v10.527H42.5");
}

</style>

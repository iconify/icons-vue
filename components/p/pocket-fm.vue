<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="wj1n7ac7w"/><path class="mkjgx0bem"/><circle class="wk_38douy"/><circle class="nooxelbfl"/><circle class="oiuavqbml"/><path class="x9oe18hed"/><path class="azyt7k26b"/><path class="hsu1a3s3m"/><path class="cp4htbq1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocket-fm" /></template>
<style>
.azyt7k26b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.306 43.5s.035-3.78.157-20.802s21.877-26.17 31.257-9.05c6.229 11.37-2.607 30.316-21.898 22.617z");
}

.cp4htbq1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.174 13.653a6.29 6.29 0 0 1 6.012 5.51");
}

.hsu1a3s3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.174 15.407a4.185 4.185 0 0 1 4.14 3.755");
}

.mkjgx0bem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.498 21.51h6.117m2.677 0h2.294");
}

.nooxelbfl {
  cx: 19.512px;
  cy: 28.421px;
  r: 0.857px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oiuavqbml {
  cx: 24.92px;
  cy: 27.246px;
  r: 1.714px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wj1n7ac7w {
  width: 17.138px;
  height: 11.996px;
  x: 12.821px;
  y: 18.671px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.055px;
}

.wk_38douy {
  cx: 15.907px;
  cy: 28.421px;
  r: 0.857px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x9oe18hed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.334 18.67l7.756-4.97m6.084 3.424a2.293 2.293 0 0 1 2.282 2.038");
}

</style>

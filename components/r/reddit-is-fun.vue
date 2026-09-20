<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vedgxt92j"/><circle class="u-woj1pbh"/><path class="epx1rngnr"/><circle class="exzd_ccmr"/><path class="fk3ks8b1r"/><path class="c2xrbabwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reddit-is-fun" /></template>
<style>
.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.epx1rngnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.165 20.44v14.513");
}

.exzd_ccmr {
  cx: 22.605px;
  cy: 16.068px;
  r: 0.75px;
  fill: currentColor;
}

.fk3ks8b1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.794 34.953V16.88a3.834 3.834 0 0 1 3.834-3.833c1.886 0 3.064.558 3.872 1.604M25.547 20.44h7.667");
}

.u-woj1pbh {
  cx: 22.165px;
  cy: 15.627px;
  r: 2.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vedgxt92j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 25.917a5.477 5.477 0 0 1 5.477-5.477m-5.477 0v14.513");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e_0c0ubey"/><path class="uxc1rib-b"/><circle class="wn0_xwaij"/><path class="n9wp5fb2l"/><circle class="bwzo9ebvp"/><path class="fhgm464ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tripletex" /></template>
<style>
.bwzo9ebvp {
  cx: 17.651px;
  cy: 36.771px;
  r: 6.729px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e_0c0ubey {
  cx: 30.349px;
  cy: 24px;
  r: 6.729px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fhgm464ky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.651 36.771V43.5");
}

.n9wp5fb2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.651 11.229l4.758-4.758");
}

.uxc1rib-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.349 24h6.73");
}

.wn0_xwaij {
  cx: 17.651px;
  cy: 11.229px;
  r: 6.729px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

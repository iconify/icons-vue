<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e--k2abqt"/><path class="sz4bu-b7i"/><path class="sjm_zjbot"/><path class="hxqij6k1y"/><path class="g5qte_1_l"/><path class="w7dl28sqx"/><path class="h-3lv6bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:speakingpal" /></template>
<style>
.e--k2abqt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1 4;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g5qte_1_l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M20.07 19.516h2.524s.281-2.565-1.278-2.565s-1.247 2.565-1.247 2.565Z");
}

.h-3lv6bvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M20.53 24.7c.855 1.726 3.597 3.35 5.308.06c.603-1.16.935-1.919 1.177-1.96c.15-.025.456.63.456.63");
}

.hxqij6k1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M24 6.233v6.447m2.867-5.756v5.756m-5.734-5.685v5.685");
}

.sjm_zjbot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.23 25.523a12 12 0 0 0 23.54 0");
}

.sz4bu-b7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6.233a7.61 7.61 0 0 1 7.61 7.61v9.42a7.61 7.61 0 0 1-15.22 0v-9.42A7.61 7.61 0 0 1 24 6.233m2.94 28.65v6.245a.64.64 0 0 1-.63.64h-4.62a.64.64 0 0 1-.63-.64v-6.245");
}

.w7dl28sqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.377 19.177a1.378 1.378 0 1 1 2.662-.713");
}

</style>

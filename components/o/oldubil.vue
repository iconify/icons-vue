<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="ldjzromgv"/><path class="wtn3ftb5d"/><circle class="m_pkn1baj"/><path class="q8o2-9byk"/><circle class="kkh7ymbay"/><path class="k0ueyimco"/><circle class="o1z8cbpeq"/><path class="l1of_5owk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oldubil" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.k0ueyimco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 37.332V24.878m10.299-2.182V10.613m.315 26.719v-8.054m3.876 8.054V24.878");
}

.kkh7ymbay {
  cx: 13.527px;
  cy: 33.305px;
  r: 4.027px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l1of_5owk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.131 37.388h8.729l1.64-7.618h-4.43c.847-2.44.904-5.168-2.005-5.088c.39 3.832-2.175 5.195-3.673 5.875");
}

.ldjzromgv {
  cx: 13.408px;
  cy: 18.789px;
  r: 3.908px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m_pkn1baj {
  cx: 26.19px;
  cy: 18.789px;
  r: 3.908px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o1z8cbpeq {
  cx: 20.114px;
  cy: 26.466px;
  r: 0.75px;
  fill: currentColor;
}

.q8o2-9byk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.097 22.696V10.613m8.403 4.268v4.856a2.96 2.96 0 0 1-5.92 0l.03-4.856");
}

.wtn3ftb5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.799 22.696V10.613");
}

</style>

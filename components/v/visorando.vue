<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="al-ok7mlp"/><circle class="m3n6qgbwi"/><circle class="l4tkcmqdj"/><circle class="xlw893bco"/><path class="dmtnzdb2k"/><path class="aqywvfl9b"/><path class="ibmh03-bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:visorando" /></template>
<style>
.al-ok7mlp {
  cx: 36.354px;
  cy: 29.108px;
  r: 7.146px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.aqywvfl9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.59 25.215l5.413-8.393l.15-1.252l-2.206-.861m19.38 13.478l-6.404-7.182l-10.92-4.183m13.333-.68l-6.09 12.034m2.912-13.889c-.758-.064 1.593 1.482 3.337 1.869s2.633-.354 2.723-1.424s-3.6-.239-6.06-.445");
}

.dmtnzdb2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.987 29.293l-9.741-1.117l-7.828-10.447");
}

.ibmh03-bc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.498 14.3c-.25-1.648-2.756-2.367-3.623-1.096s-2.13 3.467-1.125 3.19c2.832-.784 3.151 1.883 1.337 2.757m-.385-7.405l.662 1.019");
}

.l4tkcmqdj {
  cx: 11.625px;
  cy: 26.051px;
  r: 1.278px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m3n6qgbwi {
  cx: 11.625px;
  cy: 26.051px;
  r: 7.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xlw893bco {
  cx: 36.354px;
  cy: 29.108px;
  r: 1.379px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

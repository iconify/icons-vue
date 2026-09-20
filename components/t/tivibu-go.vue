<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e27g1nb5e"/><circle class="a_sx-tbnt"/><path class="g3mna7oqw"/><circle class="ducnjdhof"/><path class="qcm_uobyo"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tivibu-go" /></template>
<style>
.a_sx-tbnt {
  cx: 15.85px;
  cy: 13.906px;
  r: 0.75px;
  fill: currentColor;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ducnjdhof {
  cx: 24.45px;
  cy: 13.906px;
  r: 0.75px;
  fill: currentColor;
}

.e27g1nb5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.15 16.306l-2 5.4l-2-5.4m14.7 0v3.3c0 1.1.9 2 2 2s2-.9 2-2v-3.3m0 3.4v2");
}

.g3mna7oqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.85 16.306v5.4m-3.6-7v6c0 .6.4 1 1 1h.3m-2.4-5.4h2.2m13.4 2c0-1.1.9-2 2-2s2 .9 2 2v1.3c0 1.1-.9 2-2 2s-2-.9-2-2m0 2.1v-8m1.3 20.588zc-1.5 0-2.6-1.2-2.6-2.6v-2.7c0-1.5 1.2-2.7 2.6-2.7c1.5 0 2.7 1.2 2.7 2.7v2.6c0 1.5-1.2 2.7-2.7 2.7m-5.089-5.4c0-1.5-1.2-2.7-2.7-2.7s-2.7 1.2-2.7 2.7v2.7c0 1.5 1.2 2.6 2.7 2.6s2.7-1.2 2.7-2.6h-2.7");
}

.qcm_uobyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.45 16.306v5.4");
}

</style>

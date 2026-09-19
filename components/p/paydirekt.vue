<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="ngss7sr9i"/><circle class="zhhqkac-a"/><circle class="k556a5r6t"/><circle class="fdpxrx7_h"/><circle class="weeben4ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paydirekt" /></template>
<style>
.fdpxrx7_h {
  cx: 18.604px;
  cy: 32.657px;
  r: 1.301px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.k556a5r6t {
  cx: 28.831px;
  cy: 32.259px;
  r: 1.301px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ngss7sr9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.328 22.153a3.375 3.375 0 0 1-3.375 3.375h0a3.375 3.375 0 0 1-3.375-3.375v-2.194a3.375 3.375 0 0 1 3.375-3.375h0a3.375 3.375 0 0 1 3.375 3.375m0 5.569v-8.944m7.017 8.944l-3.595-8.944m6.75 0l-4.286 12.149c-.285.81-.541 1.564-1.91 2.225M11.5 22.153a3.375 3.375 0 0 0 3.375 3.375h0a3.375 3.375 0 0 0 3.375-3.375v-2.194a3.375 3.375 0 0 0-3.375-3.375h0A3.375 3.375 0 0 0 11.5 19.96m0-3.376v13.5");
}

.weeben4ob {
  cx: 15.625px;
  cy: 30.834px;
  r: 0.75px;
  fill: currentColor;
}

.zhhqkac-a {
  cx: 23.656px;
  cy: 33.509px;
  r: 1.907px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

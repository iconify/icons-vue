<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9off3c6t"/><path class="kav8xqbqa"/><circle class="ikxs_5bny"/><circle class="rjj3nvbwe"/><path class="a_qfupb3a"/><circle class="x1ho4cb6c"/><path class="e0ymdobwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:traingo" /></template>
<style>
.a_qfupb3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.521 4.5H31.48m-4.118 0v3.379M20.638 4.5v3.379m-9.665 25.639h26.054m-5.159-4.788a1.515 1.515 0 0 0-2.994 0");
}

.e0ymdobwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.068 33.518c-.039.99-.008 1.481-.682 1.896h-8.772c-.674-.415-.643-.905-.682-1.897");
}

.ikxs_5bny {
  cx: 17.629px;
  cy: 28.462px;
  r: 3.246px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k9off3c6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.456 7.879h21.089a2.48 2.48 0 0 1 2.482 2.484V34.57a2.48 2.48 0 0 1-2.483 2.484H13.456a2.48 2.48 0 0 1-2.483-2.484V10.363a2.48 2.48 0 0 1 2.483-2.484m2.615 32.401H31.93M14.27 43.5l3.604-6.447m12.25 0l3.604 6.447");
}

.kav8xqbqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.01 7.879h19.979v15.464H14.01z");
}

.rjj3nvbwe {
  cx: 30.371px;
  cy: 28.462px;
  r: 3.246px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x1ho4cb6c {
  cx: 16.762px;
  cy: 27.954px;
  r: 0.75px;
  fill: currentColor;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uv5fv_b-o"/><circle class="r4jkq-brt"/><path class="cs2azit9u"/><path class="ixhtb3bow"/><circle class="y_702aciq"/><circle class="pwh1ywmsq"/><path class="twimjcbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nimc-personal-id" /></template>
<style>
.cs2azit9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.916 7.504a17.78 17.78 0 0 1 9.858 9.957M4.5 22.77A17.776 17.776 0 0 1 26.962 6.84m.007 34.271A17.776 17.776 0 0 1 4.563 25.896");
}

.ixhtb3bow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.846 14.18a14.281 14.281 0 0 1 24.57 8.108M12.382 34.314a14.28 14.28 0 0 1-2.185-18.019M24.886 38.01a14.28 14.28 0 0 1-8.91-1.196");
}

.pwh1ywmsq {
  cx: 35.011px;
  cy: 31.214px;
  r: 1.705px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r4jkq-brt {
  cx: 22.235px;
  cy: 23.977px;
  r: 3.995px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.twimjcbvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.028 34.312c3.15-.034 3.542 2.034 3.542 2.034c-2.425.745-4.668.748-7.117 0c0 0 .426-2 3.575-2.034");
}

.uv5fv_b-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.148 31.116a7.39 7.39 0 0 1-8.01-2.963");
}

.y_702aciq {
  cx: 35.011px;
  cy: 33.311px;
  r: 8.489px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

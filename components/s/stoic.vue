<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c2xrbabwq"/><rect class="efyctbbdr"/><circle class="bka29hb3l"/><path class="k41chhnai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stoic" /></template>
<style>
.bka29hb3l {
  cx: 30.397px;
  cy: 18.978px;
  r: 0.75px;
  fill: currentColor;
}

.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.efyctbbdr {
  width: 5.571px;
  height: 7.381px;
  x: 21.992px;
  y: 22.39px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.785px;
  ry: 2.785px;
}

.k41chhnai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.397 22.39v7.382m-20.722-.623c.509.427 1.058.623 2.291.623h.625a1.843 1.843 0 0 0 1.841-1.846a1.843 1.843 0 0 0-1.84-1.845h-1.25A1.843 1.843 0 0 1 9.5 24.236c0-1.02.824-1.846 1.841-1.846h.625c1.233 0 1.782.196 2.291.623m4.074-2.92v8.286c0 .77.624 1.393 1.393 1.393h.418m-3.273-7.382h2.925M38.5 28.369a2.785 2.785 0 0 1-5.204-1.382v-1.811a2.784 2.784 0 0 1 5.201-1.387");
}

</style>

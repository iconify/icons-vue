<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="iq2bi8q_x"/><path class="c9ke9gbhe"/><circle class="e0goa3kui"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trainline" /></template>
<style>
.c9ke9gbhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.484 31.784v6.374m4.776-3.978a2.396 2.396 0 0 1 4.792 0v3.978m-4.792-6.374v6.374M14.49 34.18a2.396 2.396 0 0 1 2.396-2.396m-2.397 0v6.374m-3.851-9.584v9.584m-1.673-6.374h3.347m13.56 0v6.374");
}

.e0goa3kui {
  cx: 25.872px;
  cy: 29.306px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.iq2bi8q_x {
  width: 4.792px;
  height: 6.374px;
  x: 18.692px;
  y: 31.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.396px;
  ry: 2.396px;
}

</style>

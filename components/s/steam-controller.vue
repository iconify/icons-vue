<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d5nza6cbe"/><circle class="y725o6bkk"/><path class="zbcddabpj"/><circle class="e267pbcyf"/><circle class="gziru-zur"/><circle class="o4a8sedfm"/><circle class="s6cs40ywp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:steam-controller" /></template>
<style>
.d5nza6cbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.587 10.612h20.826c3.516 0 5.95 1.785 7.032 5.572c1.081 3.245 2.055 8.654 2.055 17.31c0 2.704-2.055 3.894-4.22 3.894c-1.892 0-2.974-1.19-3.623-2.272c-.703-1.353-1.515-2.164-3.138-2.164H15.481c-1.623 0-2.434.811-3.084 2.164c-.703 1.082-1.785 2.272-3.678 2.272c-2.434 0-4.219-1.19-4.219-3.895c0-8.655.974-14.064 2.056-17.31c1.081-3.786 3.515-5.57 7.031-5.57");
}

.e267pbcyf {
  cx: 31.87px;
  cy: 14.669px;
  r: 0.75px;
  fill: currentColor;
}

.gziru-zur {
  cx: 28.517px;
  cy: 18.023px;
  r: 0.75px;
  fill: currentColor;
}

.o4a8sedfm {
  cx: 35.224px;
  cy: 18.023px;
  r: 0.75px;
  fill: currentColor;
}

.s6cs40ywp {
  cx: 31.87px;
  cy: 21.431px;
  r: 0.75px;
  fill: currentColor;
}

.y725o6bkk {
  cx: 16.13px;
  cy: 18.023px;
  r: 3.029px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zbcddabpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.763 24.656a.757.757 0 0 1 .866-.63l3.847.61a.757.757 0 0 1 .63.866l-.61 3.847a.757.757 0 0 1-.866.629l-3.847-.61a.757.757 0 0 1-.63-.866zm15.267.794a.757.757 0 0 1 .644-.855l3.856-.542a.757.757 0 0 1 .856.644l.542 3.857a.757.757 0 0 1-.645.855l-3.856.542a.757.757 0 0 1-.856-.644z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="t_pmw8b6s"/><circle class="qdx13rb7h"/><circle class="j-i6o9bee"/><circle class="fqqxq02fg"/><path class="zj43clbbc"/><rect class="nsszayb1a"/><path class="ghexivb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:railwaystationphotos" /></template>
<style>
.fqqxq02fg {
  cx: 31.32px;
  cy: 31.93px;
  r: 2.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ghexivb_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.61 14.26v-2.1a.93.93 0 0 0-.92-.92h-9.38a.93.93 0 0 0-.92.92v2.1m-2.74 24.48L9.28 43.5m23.07-4.76l6.37 4.76M21.86 6.61h4.28");
}

.j-i6o9bee {
  cx: 16.68px;
  cy: 31.93px;
  r: 2.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nsszayb1a {
  width: 19.17px;
  height: 9.93px;
  x: 14.41px;
  y: 14.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.83px;
}

.qdx13rb7h {
  cx: 28.25px;
  cy: 6.61px;
  r: 2.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t_pmw8b6s {
  cx: 19.75px;
  cy: 6.61px;
  r: 2.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zj43clbbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.64 6.61h-2a4.6 4.6 0 0 0-4.59 4.59v23a4.6 4.6 0 0 0 4.59 4.59h16.7a4.6 4.6 0 0 0 4.59-4.59v-23a4.6 4.6 0 0 0-4.59-4.59h-2");
}

</style>

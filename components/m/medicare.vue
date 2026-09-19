<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x94cq-bnj"/><path class="aixvlxkfs"/><circle class="btek_jmqa"/><circle class="acs-qgk7s"/><path class="tih6c4m1w"/><circle class="xctkorosb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:medicare" /></template>
<style>
.acs-qgk7s {
  cx: 26.836px;
  cy: 35.093px;
  r: 1px;
  fill: none;
  stroke: currentColor;
}

.aixvlxkfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.643 22.75c.953 1.143 1.294 4.363-.337 5.83m-11.941-1.003c-.797-.965-.83-3.394-.909-4.609M9.05 38.178c0-4.426 1.539-11.606 6.08-13.678m23.821 13.678c0-4.279-1.438-11.13-5.637-13.454");
}

.btek_jmqa {
  cx: 23.222px;
  cy: 31.402px;
  r: 1px;
  fill: none;
  stroke: currentColor;
}

.tih6c4m1w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M23.645 30.364c.791-2.304 4.352-4.2 6.504-1.784s-.472 5.56-2.36 6.137");
}

.x94cq-bnj {
  fill: none;
  stroke: currentColor;
  d: path("M23.995 9.822c3.55 0 6.436 2.906 6.436 6.5s-2.886 6.5-6.436 6.5s-6.435-2.905-6.435-6.5s2.885-6.5 6.435-6.5Z");
}

.xctkorosb {
  cx: 19.292px;
  cy: 28.919px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
}

</style>

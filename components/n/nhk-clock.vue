<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="v23hjgubi"/><circle class="i7wdi9_uf"/><path class="vj5c4jb2j"/><circle class="vqogbbbht"/><path class="bpykrbc6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nhk-clock" /></template>
<style>
.bpykrbc6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.414 22.586l-7.778 7.778M24 12v1m0 22v1m12-12h-1m-22 0h-1");
}

.i7wdi9_uf {
  cx: 24px;
  cy: 24px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v23hjgubi {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 13.5px;
}

.vj5c4jb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.783 18.051L24 24h9");
}

.vqogbbbht {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>

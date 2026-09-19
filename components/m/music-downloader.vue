<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhxbzab6r"/><circle class="k1lpq6bwn"/><circle class="flitold-w"/><path class="t1zl9ubhi"/><circle class="iv34yub_k"/><path class="yred2ccsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-downloader" /></template>
<style>
.flitold-w {
  cx: 30.568px;
  cy: 27.837px;
  r: 3.731px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iv34yub_k {
  cx: 38.5px;
  cy: 38.499px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k1lpq6bwn {
  cx: 14.31px;
  cy: 32.507px;
  r: 3.731px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t1zl9ubhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.499v-8m-3.297 4.704l3.297 3.296l3.297-3.296");
}

.xhxbzab6r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.299 16.729l-16.258 2.254v-5.752l16.258-2.254zm0 0v11.108m-16.258-8.854v13.524");
}

.yred2ccsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43");
}

</style>

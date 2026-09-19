<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nhjpg1bgm"/><circle class="pg-23jyla"/><circle class="czlegl19g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobitech" /></template>
<style>
.czlegl19g {
  cx: 41.16px;
  cy: 14.708px;
  r: 2.341px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nhjpg1bgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.666 35.653V19.246m4.399-3.794c13.307 3.12 13.396 11.93 13.365 20.201m1.388-13.366c2.245-3.424 7.12-7.17 11.168-7.23m4.228 4.011l.09 16.585");
}

.pg-23jyla {
  cx: 6.84px;
  cy: 14.688px;
  r: 2.341px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

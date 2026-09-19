<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="iv34yub_k"/><path class="yazjg8bzf"/><path class="zgmge5yrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiktok-downloader" /></template>
<style>
.iv34yub_k {
  cx: 38.5px;
  cy: 38.499px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yazjg8bzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43M38.5 42.499v-8");
}

.zgmge5yrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.203 39.203l3.297 3.296l3.297-3.296M21.43 23.22a5.14 5.14 0 1 0 5.135 5.165V14.5a5.14 5.14 0 0 0 5.14 5.14");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="iv34yub_k"/><path class="yred2ccsw"/><path class="ims7c753b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:video-downloader" /></template>
<style>
.ims7c753b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.76 24l-14.722-8.5v17zm4.74 18.499v-8m-3.297 4.704l3.297 3.296l3.297-3.296");
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

.yred2ccsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43");
}

</style>

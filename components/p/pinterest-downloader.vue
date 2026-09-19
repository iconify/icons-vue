<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="iv34yub_k"/><path class="yazjg8bzf"/><path class="aaza82beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pinterest-downloader" /></template>
<style>
.aaza82beo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.203 39.203l3.297 3.296l3.297-3.296M19.356 34.5s3.522-14.666 3.87-15.586c-4.134.31-2.71 8.2 1.525 9.068c3.226.755 6.8-2.983 6.748-7.13s-2.49-6.216-5.572-7.077s-7.984.204-9.285 4.515a6.92 6.92 0 0 0 1.971 7.536");
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

.yazjg8bzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43M38.5 42.499v-8");
}

</style>

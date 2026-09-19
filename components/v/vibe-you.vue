<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h2ku5jvmo"/><ellipse transform="rotate(-27.452 20.184 32.885)" class="b_cgz1wcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vibe-you" /></template>
<style>
.b_cgz1wcs {
  cx: 20.184px;
  cy: 32.885px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.097px;
  ry: 3.598px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h2ku5jvmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.07 30.666s2.996-5.071 2.47-8.378C31.965 18.658 25 13.353 25 11.83c-.028-.848.03-1.691 0-2.54v22.523");
}

</style>

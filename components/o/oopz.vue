<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="y99az2tox"/><circle class="v5_7zabyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oopz" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v5_7zabyf {
  cx: 34.403px;
  cy: 33.635px;
  r: 0.75px;
  fill: currentColor;
}

.y99az2tox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.93 13.29c4.977-.027 9.955-.054 12.843-.067s3.687-.013 4.169.202s.646.647.634 1.122s-.203.995-1.61 2.536s-4.032 4.101-6.657 6.662m-1.789-.016c-2.463 2.399-4.927 4.798-6.293 6.188c-1.365 1.39-1.631 1.77-1.707 2.22s.038.97.266 1.306s.57.488 3.533.53s8.547-.024 14.13-.092");
}

</style>

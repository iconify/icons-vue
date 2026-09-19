<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="qscbn3byp"/><circle class="yl94lpfnl"/><path class="rcbx32z_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsungpaymini" /></template>
<style>
.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qscbn3byp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.348 20.4H43.5v7.2h-7.152a2.85 2.85 0 0 1-2.848-2.848v-1.504a2.85 2.85 0 0 1 2.848-2.848");
}

.rcbx32z_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.416 28.473c.758.636 1.576.928 3.414.928h.931a2.747 2.747 0 0 0 2.744-2.75h0a2.747 2.747 0 0 0-2.744-2.75H17.9a2.747 2.747 0 0 1-2.744-2.75h0a2.747 2.747 0 0 1 2.744-2.75h.931c1.838 0 2.656.292 3.414.928");
}

.yl94lpfnl {
  cx: 36.472px;
  cy: 24px;
  r: 0.795px;
  fill: currentColor;
}

</style>

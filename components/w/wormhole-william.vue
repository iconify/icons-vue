<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="x0vdpu6ys"/><path class="npwyti-xx"/><path class="b_-aavq5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wormhole-william" /></template>
<style>
.b_-aavq5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.18 28.649c-.719 2.137 2.045 2.867 2.045 7.143s-4.901 5.943-7.821 5.943s-3.494-1.381-5.397-1.381a1.81 1.81 0 0 1-1.929-2.073a1.88 1.88 0 0 1 1.245-1.855");
}

.npwyti-xx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.774 30.838c3.638 4.328 16.881 8.134 16.881 8.134");
}

.x0vdpu6ys {
  cx: 24px;
  cy: 19.151px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 12.886px;
}

</style>

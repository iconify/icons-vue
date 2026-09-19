<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="evt5dacue"/><path class="qhjym7y1b"/><path class="ruh9b3wzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallth" /></template>
<style>
.evt5dacue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42 29.4V39a1.996 1.996 0 0 1-2 2H6a1.996 1.996 0 0 1-2-2V12a1.996 1.996 0 0 1 2-2h34a1.996 1.996 0 0 1 2 2v10");
}

.qhjym7y1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 10a3.375 3.375 0 0 1 3-3h28a3.375 3.375 0 0 1 3 3m4.5 12v7.4H37a4 4 0 0 1-4.054-3.7A4.016 4.016 0 0 1 37 22ZM17 26l6 9l6-9l-6-10.263Z");
}

.ruh9b3wzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17 26l6 4l6-4");
}

</style>

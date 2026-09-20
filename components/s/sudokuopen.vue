<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhaw-tjxu"/><circle class="htunhgpjo"/><path class="meq2c8zbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sudokuopen" /></template>
<style>
.htunhgpjo {
  cx: 37.07px;
  cy: 25.57px;
  r: 2.69px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.meq2c8zbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.46 21.19a2.45 2.45 0 0 0-2.19-1h-.2a2.69 2.69 0 0 0-2.7 2.69v2.69M42.5 18h-37m37 12.46h-37");
}

.qhaw-tjxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.41 5.5v37m12.09-37v37M9.94 15.35h3.99M9.94 8.47l2-1.09m0 0v7.97m22.5-.52a2.78 2.78 0 0 0 2.1.61h.27a2.32 2.32 0 0 0 2.28-2.28a2.32 2.32 0 0 0-2.28-2.28h-2.37V8.42h4.65M26.35 28.24v-8l-4.29 5.38h5.29");
}

</style>

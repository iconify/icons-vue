<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0hba3b0o"/><rect class="h-87aectj"/><path class="u1sy8fb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quickdic" /></template>
<style>
.h-87aectj {
  width: 5.58px;
  height: 7.43px;
  x: 28.58px;
  y: 22.19px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.79px;
}

.u1sy8fb9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.16 22.19v7.43");
}

.z0hba3b0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.45v35.1a2 2 0 0 0 1.95 2h2.38V4.5h-2.38A2 2 0 0 0 8.4 6.45m4.33-1.95v39h24.92a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95Zm5.43 25.09l3.76-11.21m3.6 11.24l-3.6-11.24m2.39 7.48h-4.9");
}

</style>

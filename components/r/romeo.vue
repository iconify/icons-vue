<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tnrojhb2x"/><path class="egxyvibwj"/><path class="up-sc8b8n"/><path class="mbda3pbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:romeo" /></template>
<style>
.egxyvibwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.87 20.46c2.48-2.14 3.06-5.52 1.31-7.54S19 11 16.52 13.15s-3.42 5.68-1.66 7.7s5.54 1.76 8.01-.39");
}

.mbda3pbjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.34 36.53c7.66 0 24.92-6.07 24.92-20.24a11.4 11.4 0 0 0-1.39-6.07l2.47-1.71s3.16 2.49 3.16 9.3c0 9.93-9.5 24.79-29.16 24.79Z");
}

.tnrojhb2x {
  cx: 9.42px;
  cy: 26.15px;
  r: 3.92px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.up-sc8b8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.85 16.81c0-5.52 6.71-11.41 15.29-11.41c6.47 0 10.71 4.44 10.71 10.7S27.83 32 17.33 32v-5c3.22 0 12.14-2.15 12.14-11.26c0-6-4.17-7.33-7.37-7.33c-5 0-10.76 4-10.76 8.36Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h5w7ntpwh"/><circle class="f6pwnu2qy"/><circle class="pl-wftb2b"/><path class="d7kupy-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:worm" /></template>
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

.d7kupy-yv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.423 28.423c-.477 2.327-2.958 3.07-5.215 2.593m1.572-15.059c-8.47.06-11.521 5.48-10.177 11.04M15.88 9.598c-7.167 2.276-9.548 8.854-7.839 13.888");
}

.f6pwnu2qy {
  cx: 25.458px;
  cy: 27.673px;
  r: 0.75px;
  fill: currentColor;
}

.h5w7ntpwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.09 8.53c.39.01.78.04 1.17.07c9.56.82 17.87 5.81 23.41 14.03c2.31 3.43 1.4 8.09-2.03 10.41a7.5 7.5 0 0 1-4.18 1.28c-2.42 0-4.78-1.16-6.23-3.31c-3.79-5.62-8.76-7.17-12.27-7.47c-2.17-.19-4.38.05-6.45.67");
}

.pl-wftb2b {
  cx: 29.53px;
  cy: 25.521px;
  r: 0.75px;
  fill: currentColor;
}

</style>

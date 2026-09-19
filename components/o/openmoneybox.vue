<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2ivy79ko"/><path class="sp287pbub"/><circle class="xf59nwbpu"/><path class="fhv4t_3ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openmoneybox" /></template>
<style>
.fhv4t_3ey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.12 14.13L13.19 6.87l-2.11 7.26");
}

.i2ivy79ko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.7 23.25v-7.12a2 2 0 0 1 2-2h32.8a2 2 0 0 1 2 2v23a2 2 0 0 1-2 2H8.7a2 2 0 0 1-2-2V32");
}

.sp287pbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.25H17a2 2 0 0 1 2 2V30a2 2 0 0 1-2 2H5.5a1 1 0 0 1-1-1v-6.75a1 1 0 0 1 1-1");
}

.xf59nwbpu {
  cx: 14.49px;
  cy: 27.63px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

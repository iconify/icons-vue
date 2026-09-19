<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x67ep52ao"/><path class="xw6sxcb_u"/><circle class="sqji1en_t"/><path class="jy772ob6b"/><circle class="r3-1ohb_s"/><path class="ekw3r285v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tilla" /></template>
<style>
.ekw3r285v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.386 31.95c0 1.876-1.515 7.102-3.383 7.102s-3.384-5.226-3.384-7.101a3.384 3.384 0 1 1 6.767 0M9.24 17.272a30 30 0 0 0 4.355 3.017c2.039 1.15 4.427 1.627 6.41 2.873a17.1 17.1 0 0 1 3.997 3.373a30 30 0 0 1 3.316-2.86c2.046-1.321 4.552-1.803 6.624-3.084c2.167-1.34 4.489-3.168 4.489-3.168");
}

.jy772ob6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.627 24.763c-3.307.605-10.513 1.846-10.187 4.366a6.33 6.33 0 0 0 3.793 2.696c4.82.75 7.93-7.398 6.394-7.062");
}

.r3-1ohb_s {
  cx: 32.889px;
  cy: 28.139px;
  r: 1.992px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sqji1en_t {
  cx: 15.264px;
  cy: 28.139px;
  r: 1.992px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x67ep52ao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.842 43.325a17 17 0 0 0-5.01-2.195c-7.802-1.748-14.35-7.105-13.218-14.506c.383-3.692 3.626-9.352 3.626-9.352c-2.628-3.016-5.446-5.826-4.58-12.597c1.14 3.23 2.245 6.507 4.962 7.634c-1.17-1.857-.659-3.354-.668-4.962a7.81 7.81 0 0 0 4.676 5.63c8.477-5.594 14.603-3.778 20.136-.095c2.969-.833 4.71-2.622 5.249-5.344a4.76 4.76 0 0 1-.573 4.676c3.532-1.114 3.75-4.682 5.058-7.444c-.172 5.392-1.372 10.063-5.07 12.654c0 0 3.813 5.696 3.567 9.893c-.543 9.936-6.247 12.337-12.506 13.74c-2.111.472-3.951 1.67-5.65 2.268Z");
}

.xw6sxcb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.526 24.763c3.307.605 10.513 1.846 10.187 4.366a6.33 6.33 0 0 1-3.793 2.696c-4.82.75-7.93-7.398-6.394-7.062");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uyj_npkmo"/><path class="cvmhsybgn"/><path class="c-8nyiwea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:suntimescalendars" /></template>
<style>
.c-8nyiwea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.75 36.73H9.26V16.26h24.05v2.64M18 30.67h24.05");
}

.cvmhsybgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.62 20.42V8.78h-4.29V5.5h-3.64v3.28H13.83V5.5h-3.6v3.28H6v30.71h16.07");
}

.uyj_npkmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 18.45a12 12 0 1 0 12 12a12 12 0 0 0-12-12");
}

</style>

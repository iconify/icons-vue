<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9i0tvclr"/><path class="w7ko4sbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:untrackme" /></template>
<style>
.k9i0tvclr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.89 15.13l6.59 6.43L25.89 28l-.05-3.66c-5.31.23-6.74 1.22-10.17 4.54c2-10.16 11-10.18 10.15-10Z");
}

.w7ko4sbft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.07 10.1L26.28 4.92a5.6 5.6 0 0 0-4.26 0L8.89 10.1A2 2 0 0 0 7.62 12v12.47c0 11.16 11.6 19 16.58 19s16.18-7.87 16.18-19V12a2 2 0 0 0-1.31-1.9");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="npma69bsg"/><circle class="cpk0fnbgt"/><circle class="c3f-hsbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obs-blade" /></template>
<style>
.c3f-hsbol {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.npma69bsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.516 18.206c2.47-13.09 18.55-17.52 28.44-8.66c9.68 9.99 3.4 22.56-8.86 25.14c13.29-5.15 13.6-16.79 5.66-23.8c-9.27-7.21-22.15-2.27-25.24 7.32m32.98 11.41c-2.98 9.61-15.8 14.7-25.15 7.6c-8.01-6.92-7.84-18.57 5.4-23.87c-12.23 2.72-18.38 15.36-8.58 25.24c9.99 8.75 26.01 4.14 28.33-8.97");
}

</style>

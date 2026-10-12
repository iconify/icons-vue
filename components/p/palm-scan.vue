<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3-t4zbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palm-scan" /></template>
<style>
.e3-t4zbss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V5A2.25 2.25 0 0 1 5 2.75h2.5m9 0H19A2.25 2.25 0 0 1 21.25 5v2.5m0 9V19A2.25 2.25 0 0 1 19 21.25h-2.5m-9 0H5A2.25 2.25 0 0 1 2.75 19v-2.5m3.25-3V9a1.5 1.5 0 0 1 3 0V7.5a1.5 1.5 0 0 1 3 0V8a1.5 1.5 0 0 1 3 0v1a1.5 1.5 0 0 1 3 0v4.5a6 6 0 0 1-12 0M9 9v2.5m3-4v4M15 8v3.5");
}

</style>

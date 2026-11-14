<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdd-grbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sensor-temperature-chip" /></template>
<style>
.mdd-grbto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 8h5.75A2.625 2.625 0 0 1 14 10.625v2.75A2.625 2.625 0 0 1 11.375 16h-5.75A2.625 2.625 0 0 1 3 13.375v-2.75A2.625 2.625 0 0 1 5.625 8M5.5 16v4m3-4v4m3-4v4m5.5-6V6a1.75 1.75 0 0 1 3.5 0v8a3.25 3.25 0 1 1-3.5 0");
}

</style>

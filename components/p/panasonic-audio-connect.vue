<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zyhuw_yfj"/><path class="m2np63s9k"/><path class="ps3z7yb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panasonic-audio-connect" /></template>
<style>
.m2np63s9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.063 23.957a17 17 0 1 1 33.873.026");
}

.ps3z7yb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.016 21.821C10.378 14.361 16.532 8.5 24 8.501c7.475 0 13.63 5.871 13.984 13.337");
}

.zyhuw_yfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 22.5c5.523 0 10 4.477 10 10s-4.477 10-10 10zm-17 0c-5.523 0-10 4.477-10 10s4.477 10 10 10z");
}

</style>

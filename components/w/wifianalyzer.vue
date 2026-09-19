<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s2s75y1gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifianalyzer" /></template>
<style>
.s2s75y1gm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 23.87A24.38 24.38 0 0 1 24 14h0a24.38 24.38 0 0 1 19.5 9.85m-32 5.23A15.69 15.69 0 0 1 24 22.55a15.69 15.69 0 0 1 12.53 6.55M18 34a7.52 7.52 0 0 1 12 0");
}

</style>

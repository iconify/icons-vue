<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5k6mccwu"/><path class="hrll78j7d"/><path class="gpjxlrbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rootexplorer" /></template>
<style>
.gpjxlrbtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.22 34.4V23H34a3.82 3.82 0 0 1 0 7.64h-3.78m3.81.03l3.78 3.77");
}

.hrll78j7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37h0Z");
}

.m5k6mccwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11h0v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13Z");
}

</style>

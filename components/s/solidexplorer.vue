<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5k6mccwu"/><path class="hrll78j7d"/><path class="dv-g1ab_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:solidexplorer" /></template>
<style>
.dv-g1ab_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.85 30.8a5.13 5.13 0 0 1-9.59 2.55l2.3-2.35a5.14 5.14 0 0 1 2.81-9.46h0a5.13 5.13 0 0 1 4.48 2.59l-2.35 2.35a5.13 5.13 0 0 1 2.35 4.32Zm-7.29.2l4.94-4.52");
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

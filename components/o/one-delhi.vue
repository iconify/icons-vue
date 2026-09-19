<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6dka4v4q"/><path class="gctd41b5o"/><circle class="aef99yura"/><path class="tv_klrhmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:one-delhi" /></template>
<style>
.aef99yura {
  cx: 9.14px;
  cy: 24px;
  r: 5.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gctd41b5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.14 29.64h7.078a2.82 2.82 0 0 0 2.82-2.82v-5.64a2.82 2.82 0 1 1 5.64 0v5.64a2.82 2.82 0 1 0 5.64 0v-5.64a2.82 2.82 0 0 1 2.82-2.82h4.993");
}

.tv_klrhmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 24h-9.189");
}

.w6dka4v4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 29.64h-6.37a2.82 2.82 0 0 1-2.82-2.82v-5.64a2.82 2.82 0 0 1 2.82-2.82h6.37");
}

</style>

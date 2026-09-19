<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="uhx3m_1tm"/><circle class="s1fgo5ygt"/><path class="ljijc4i5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vendroid" /></template>
<style>
.ljijc4i5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.5v-1h2v2h-1m4 6l1-1h1l1-1h1m-12 1h1l1 1h2l1 1m2 1v1m6-2v1h-1v1h-1v2m-1-13h1l2 2v3h1v3h1v4l-1-.025v1.024h-6v-1h-3v1h-7v-1h-5l-2-2v-4l2-2v-1l1-1h1l1-1h2l3-3l1 1v1h4v-1l3-3l1 1zm-1-4l1 1v4l2 2v5l-2 2h-1l-1 1h-7l-3-3v-1l-1-1v-3l1-1v-1l3-3l1 1v1h4v-1z");
}

.s1fgo5ygt {
  cx: 24px;
  cy: 7.829px;
  r: 0.75px;
  fill: currentColor;
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>

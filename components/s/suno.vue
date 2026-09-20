<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g791itbbd"/><rect class="ecmc6dbax"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:suno" /></template>
<style>
.ecmc6dbax {
  width: 5.631px;
  height: 8.5px;
  x: 32.966px;
  y: 19.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.816px;
  ry: 2.816px;
}

.g791itbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.179 28.25v-8.5l5.631 8.5v-8.5M9.57 27.319c.522.678 1.176.931 2.085.931h1.258a2.12 2.12 0 0 0 2.12-2.12v-.01a2.12 2.12 0 0 0-2.12-2.12h-1.388a2.123 2.123 0 0 1-2.123-2.123c0-1.175.953-2.127 2.128-2.127h1.251c.91 0 1.563.253 2.084.931m2.359-.931v5.684a2.816 2.816 0 0 0 5.631 0V19.75");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>

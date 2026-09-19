<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jplb9pb4e"/><path class="rpfjxu03k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metroplayer" /></template>
<style>
.jplb9pb4e {
  cx: 8.16px;
  cy: 38.57px;
  r: 3.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rpfjxu03k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.85 5.78a3.64 3.64 0 0 0-3.2 1.91h0L24 30.91L11.37 7.69a3.66 3.66 0 0 0-6.43 3.5L20.79 40.3a3.63 3.63 0 0 0 6.41 0h0l9-16.49v14.76a3.66 3.66 0 0 0 7.31 0h0V9.43a3.65 3.65 0 0 0-3.66-3.65");
}

</style>

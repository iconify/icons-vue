<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ycvi2ubmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xunlei-browser" /></template>
<style>
.ycvi2ubmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 8.393L29.2 21.85H18.8L5.5 8.393m37 31.214L29.2 26.15H18.8L5.5 39.607");
}

</style>

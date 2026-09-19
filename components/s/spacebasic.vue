<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k_0j4ab0z"/><path class="j24slubmr"/><path class="b42jckbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spacebasic" /></template>
<style>
.b42jckbjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 30.167a6.167 6.167 0 1 0 0 12.333h24.667a6.167 6.167 0 1 0 0-12.333z");
}

.j24slubmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.026 7.306l24.667 24.667a6.167 6.167 0 0 1-8.72 8.72L7.305 16.028a6.167 6.167 0 0 1 8.72-8.72");
}

.k_0j4ab0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 5.5A6.167 6.167 0 0 0 5.5 11.666h0a6.167 6.167 0 0 0 6.167 6.167h24.667a6.167 6.167 0 1 0 0-12.333z");
}

</style>

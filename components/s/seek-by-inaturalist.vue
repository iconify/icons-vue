<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h_hiu2bwh"/><path class="qjj701bii"/><path class="ponlj-bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seek-by-inaturalist" /></template>
<style>
.h_hiu2bwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 10.482c-1.96 45.487-30.731 17.697-39 26.716c2.213-44.666 32.18-16.956 39-26.716");
}

.ponlj-bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.397 16.324c4.931.338 6.996 2.515 8.639 4.545c-2.904.724-5.706 1.61-7.041 4.818");
}

.qjj701bii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.216 28.784c6.405-9.858 14.99-9.467 23.82-7.915");
}

</style>

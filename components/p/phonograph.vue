<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k1y4b4faf"/><path class="ifu-ee78w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phonograph" /></template>
<style>
.ifu-ee78w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.08 29.15a46 46 0 0 0-7.65 3.9");
}

.k1y4b4faf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.63 25L18.24 4.64a.48.48 0 0 0-.82.31l-.24 3.4a19 19 0 0 1-.95 4.65L9.77 31.92a8.56 8.56 0 1 0 14.3-2.78L30.26 27a19 19 0 0 1 4.67-.95l3.39-.24a.48.48 0 0 0 .31-.81M17.78 37.26a2.32 2.32 0 1 1 2.33-2.32a2.32 2.32 0 0 1-2.33 2.32");
}

</style>

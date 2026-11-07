<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="voeieob5r"/><path class="hqbx6hbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-duocolor" /></template>
<style>
.hqbx6hbpx {
  d: path("M6 16V9a2 2 0 0 1 2-2h7m3 3v5a2 2 0 0 1-2 2h-5m1 0v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.voeieob5r {
  stroke-opacity: 0.4;
  d: path("M9 3v4m6-4v4M2 20L20 2");
}

</style>

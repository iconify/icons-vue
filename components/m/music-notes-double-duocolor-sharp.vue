<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ueu9_gasu"/><path class="pltfumcxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-double-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pltfumcxx {
  d: path("M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12-2a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 2V7l12-4v13");
}

.ueu9_gasu {
  stroke-opacity: 0.4;
  d: path("m9 12l12-4");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ueu9_gasu"/><path class="d-ncgbc4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-double-duocolor" /></template>
<style>
.d-ncgbc4q {
  d: path("M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12-2a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 2V9c0-.995.403-1.8 1-2l9-3c.984-.328 2 .18 2 1v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ueu9_gasu {
  stroke-opacity: 0.4;
  d: path("m9 12l12-4");
}

</style>

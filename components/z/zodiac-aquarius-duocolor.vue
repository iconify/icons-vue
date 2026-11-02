<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rst98qbxf"/><path class="ut8kv4wom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-aquarius-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rst98qbxf {
  stroke-opacity: 0.4;
  d: path("m3 17l2-2a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l2 2");
}

.ut8kv4wom {
  d: path("m3 10l2-2a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l2 2");
}

</style>

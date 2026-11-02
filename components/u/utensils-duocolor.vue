<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nz1t31b3r"/><path class="xssdch4px"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nz1t31b3r {
  stroke-opacity: 0.4;
  d: path("M3 3v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V3M7 3v18");
}

.xssdch4px {
  d: path("M21 14V3a5 5 0 0 0-5 5v4a2 2 0 0 0 2 2zm0 0v7");
}

</style>

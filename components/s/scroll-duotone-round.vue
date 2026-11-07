<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ky0yg-b6r"/><path class="fy04l3bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scroll-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fy04l3bjs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 17V7a4 4 0 0 0-4-4H5m2 2v14M7 5a2 2 0 1 0-4 0v2a1 1 0 0 0 1 1h3m0 11a2 2 0 1 0 4 0v-1a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v1a2 2 0 0 1-2 2H9");
}

.ky0yg-b6r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 2a5 5 0 0 1 5 5v9h1a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9H4a2 2 0 0 1-2-2V5a3 3 0 0 1 3-3Z");
}

</style>

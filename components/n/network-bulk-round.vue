<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w66e6qboz"/><path class="g5i7-kdnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g5i7-kdnk {
  d: path("M11 8a1 1 0 0 1 2 0v3h1a4.98 4.98 0 0 1 3.536 1.464A5 5 0 0 1 19 16a1 1 0 0 1-2 0a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 10 11h1Z");
}

.w66e6qboz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3ZM2 18a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm12 0a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Z");
}

</style>

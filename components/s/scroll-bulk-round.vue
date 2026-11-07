<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="egugoackw"/><path class="abkhehb3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scroll-bulk-round" /></template>
<style>
.abkhehb3b {
  d: path("M8 5v3a1 1 0 0 1-1 1H4a2 2 0 0 1-2-2V5a3 3 0 1 1 6 0M6 5a1 1 0 0 0-2 0v2h2Zm4 13a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a1 1 0 0 1 0-2a1 1 0 0 0 1-1Zm2 0v1c.001.341-.057.679-.171 1H19a1 1 0 0 0 1-1v-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.egugoackw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h9a5 5 0 0 1 5 5v9h1a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9H4a2 2 0 0 1-2-2V5a3 3 0 0 1 3-3");
}

</style>

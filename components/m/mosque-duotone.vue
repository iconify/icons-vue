<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fd61zlbnr"/><path class="nvw0febma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:mosque-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fd61zlbnr {
  d: path("M208 128H48c0-64 80-72 80-104c0 32 80 40 80 104");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nvw0febma {
  d: path("M224 128a23.8 23.8 0 0 0-8 1.38V128c0-41.78-31.07-62.46-53.76-77.56C148.16 41.06 136 33 136 24a8 8 0 0 0-16 0c0 9-12.16 17.06-26.24 26.44C71.07 65.54 40 86.22 40 128v1.38A24 24 0 0 0 8 152v56a8 8 0 0 0 8 8h64a8 8 0 0 0 8-8v-32a8 8 0 0 1 16 0v32a8 8 0 0 0 8 8h32a8 8 0 0 0 8-8v-32a8 8 0 0 1 16 0v32a8 8 0 0 0 8 8h64a8 8 0 0 0 8-8v-56a24 24 0 0 0-24-24M40 200H24v-48a8 8 0 0 1 16 0Zm62.63-136.24c9.67-6.44 19-12.68 25.37-20c6.34 7.35 15.7 13.59 25.37 20c20 13.32 42.48 28.29 46.11 56.24h-143c3.67-27.95 26.12-42.92 46.15-56.24M200 200h-16v-24a24 24 0 0 0-48 0v24h-16v-24a24 24 0 0 0-48 0v24H56v-64h144Zm32 0h-16v-48a8 8 0 0 1 16 0Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="tkrsc0r5j"/><path class="l-b2mxlvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:share-network-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l-b2mxlvx {
  d: path("M176 160a39.9 39.9 0 0 0-28.62 12.09l-46.1-29.63a39.8 39.8 0 0 0 0-28.92l46.1-29.63a40 40 0 1 0-8.66-13.45l-46.1 29.63a40 40 0 1 0 0 55.82l46.1 29.63A40 40 0 1 0 176 160m0-128a24 24 0 1 1-24 24a24 24 0 0 1 24-24M64 152a24 24 0 1 1 24-24a24 24 0 0 1-24 24m112 72a24 24 0 1 1 24-24a24 24 0 0 1-24 24");
}

.tkrsc0r5j {
  d: path("M208 200a32 32 0 1 1-32-32a32 32 0 0 1 32 32M176 88a32 32 0 1 0-32-32a32 32 0 0 0 32 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

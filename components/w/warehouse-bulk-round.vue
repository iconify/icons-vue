<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xyta0kxfq"/><path class="lfxipybne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lfxipybne {
  d: path("M3 22a1 1 0 0 1 0-2h5v-7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v7h5a1 1 0 0 1 0 2Zm11-6v-2h-4v2Zm0 4v-2h-4v2Z");
}

.xyta0kxfq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21v-9c0-1.693 1.069-3.152 2.553-3.894l4-2A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l4 2C18.931 8.848 20 10.307 20 12v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1");
}

</style>

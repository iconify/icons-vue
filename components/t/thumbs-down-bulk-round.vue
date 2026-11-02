<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qy6my2z1s"/><path class="zvpr52bet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qy6my2z1s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 15a3 3 0 0 1-3-3V5a3.001 3.001 0 0 1 5-2.236A3 3 0 0 1 9 2h8c1.309 0 2.675.525 3.458 1.613c.258.355.436.761.523 1.191l1 5Q22 9.901 22 10v1a4 4 0 0 1-4 4h-1a.997.997 0 0 0-1 1v3a3 3 0 1 1-6 0v-1a3 3 0 0 0-3-3Z");
}

.zvpr52bet {
  d: path("M2 12V5a3 3 0 1 1 6 0v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3m4 1V5a1 1 0 0 0-2 0v7a.997.997 0 0 0 1 1Z");
}

</style>

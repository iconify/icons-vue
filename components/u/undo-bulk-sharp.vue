<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ikb8-47xq"/><path class="z3qrhpbom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:undo-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ikb8-47xq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.384 12a7.617 7.617 0 1 1 15.233 0a7.617 7.617 0 1 1-15.233 0");
}

.z3qrhpbom {
  d: path("M5.001 10H5a.997.997 0 0 1-1-1V3a1 1 0 0 1 2 0v2.817a8.616 8.616 0 1 1-1.919 9.577a.999.999 0 1 1 1.838-.788a6.614 6.614 0 0 0 7.334 3.888A6.616 6.616 0 1 0 6.729 8H11a1 1 0 0 1 0 2Z");
}

</style>

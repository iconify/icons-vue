<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ajvp0bcfw"/><path class="qixne6ben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-bulk-sharp" /></template>
<style>
.ajvp0bcfw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.707 2.293l4 4A1 1 0 0 1 22 7v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h14c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qixne6ben {
  d: path("M9 6h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2M6 21v-7a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v7a1 1 0 0 1-2 0v-6H8v6a1 1 0 0 1-2 0");
}

</style>

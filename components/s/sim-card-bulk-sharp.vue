<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n8ygu6bwf"/><path class="jhwfuz-5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jhwfuz-5s {
  d: path("M15 8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1Zm-1 4v-2h-4v2Zm-4 2v2h4v-2Z");
}

.n8ygu6bwf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h10c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m1 6v10a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2");
}

</style>

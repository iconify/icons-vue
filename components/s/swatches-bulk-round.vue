<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v9w8nbb3z"/><path class="x8ivgm1hy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v9w8nbb3z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 10 0v10a5 5 0 0 1-10 0Z");
}

.x8ivgm1hy {
  d: path("m10.293 8.293l2-2a3.83 3.83 0 0 1 5.414 0l1 1a3.83 3.83 0 0 1 0 5.414l-.312.312A4 4 0 0 1 22 17v1a4 4 0 0 1-4 4H7a1 1 0 0 1 0-2h1.586l8.707-8.707a1.83 1.83 0 0 0 0-2.586l-1-1a1.83 1.83 0 0 0-2.586 0l-2 2a.999.999 0 1 1-1.414-1.414M11.414 20H18a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2h-1.586ZM7 16h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>

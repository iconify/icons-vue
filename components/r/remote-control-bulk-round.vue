<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oic_uxlcr"/><path class="qsq1bccwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:remote-control-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oic_uxlcr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 6a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v12a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Z");
}

.qsq1bccwz {
  d: path("M13 3v2a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m-4 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-1 4h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-4 3h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2");
}

</style>

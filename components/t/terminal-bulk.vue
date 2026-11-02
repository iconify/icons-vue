<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="trdjr4bpx"/><path class="nykaf1bdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:terminal-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nykaf1bdx {
  d: path("m7.707 8.293l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L8.586 12L6.293 9.707a.999.999 0 1 1 1.414-1.414M13 14h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.trdjr4bpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>

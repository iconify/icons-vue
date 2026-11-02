<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u0oa5x7sc"/><path class="irgtqvb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.irgtqvb1c {
  d: path("M8.707 7.293a.999.999 0 1 1-1.414 1.414l-4-4a.999.999 0 1 1 1.414-1.414ZM11 10h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2m8.707 4.293a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a.999.999 0 1 1 1.414-1.414l2 2a.414.414 0 0 0 .586 0l2-2a.414.414 0 0 0 0-.586l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

.u0oa5x7sc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.287 3.042l10 3a1 1 0 0 1 .607.511l3 6a1 1 0 0 1-.187 1.154l-4 4a1 1 0 0 1-1.154.187l-6-3a1 1 0 0 1-.511-.607l-3-10a1 1 0 0 1 1.245-1.245");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u0oa5x7sc"/><path class="imq8v6i7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.imq8v6i7o {
  d: path("M8.707 7.293a.999.999 0 1 1-1.414 1.414l-4-4a.999.999 0 1 1 1.414-1.414ZM11 10h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2m7.707 3.293a3.828 3.828 0 0 1-5.414 5.414l-1-1a.999.999 0 1 1 1.414-1.414l1 1a1.829 1.829 0 0 0 2.586-2.586l-1-1a.999.999 0 1 1 1.414-1.414Z");
}

.u0oa5x7sc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.287 3.042l10 3a1 1 0 0 1 .607.511l3 6a1 1 0 0 1-.187 1.154l-4 4a1 1 0 0 1-1.154.187l-6-3a1 1 0 0 1-.511-.607l-3-10a1 1 0 0 1 1.245-1.245");
}

</style>

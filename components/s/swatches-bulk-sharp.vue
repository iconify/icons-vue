<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u38387k-h"/><path class="i413o4i1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i413o4i1i {
  d: path("m10.293 8.293l4-4a1 1 0 0 1 1.414 0l5 5a1 1 0 0 1 0 1.414L18.414 13H21a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H7a1 1 0 0 1 0-2h1.586l10-10L15 6.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414M11.414 20H20v-5h-3.586ZM7 16h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

.u38387k-h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v14a5 5 0 0 1-10 0Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u0oa5x7sc"/><path class="yl68s0ndg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u0oa5x7sc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.287 3.042l10 3a1 1 0 0 1 .607.511l3 6a1 1 0 0 1-.187 1.154l-4 4a1 1 0 0 1-1.154.187l-6-3a1 1 0 0 1-.511-.607l-3-10a1 1 0 0 1 1.245-1.245");
}

.yl68s0ndg {
  d: path("M8.707 7.293a.999.999 0 1 1-1.414 1.414l-4-4a.999.999 0 1 1 1.414-1.414ZM11 10h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2m9.707 5.293a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L16 18.586L18.586 16l-2.293-2.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>

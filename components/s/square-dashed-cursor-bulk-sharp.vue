<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gzcjrcf9o"/><path class="ikcjaqvud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gzcjrcf9o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l1.751 1.751a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-1.751-1.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265");
}

.ikcjaqvud {
  d: path("M3 2h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1m11 2h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m8-1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2h3a1 1 0 0 1 1 1M9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l1.751 1.751a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-1.751-1.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265M4 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m8.863 7.426l.167-.669a1 1 0 0 1 1.677-.464L17 18.586L18.586 17l-2.293-2.293a1 1 0 0 1 .464-1.677l.669-.167l-6.845-2.282ZM2 21v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1");
}

</style>

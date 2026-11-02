<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="um-8nqbwo"/><path class="yzlz-dvnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.um-8nqbwo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l.751.751a2.414 2.414 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0l-.751-.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265");
}

.yzlz-dvnt {
  d: path("M5 2h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0V5a3 3 0 0 1 3-3m9 2h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m8 1v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3 3 0 0 1 3 3M9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l.751.751a2.414 2.414 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0l-.751-.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265M4 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m8.863 7.426l.167-.669a1 1 0 0 1 1.677-.464l2 2a.414.414 0 0 0 .586 0l1-1a.414.414 0 0 0 0-.586l-2-2a1 1 0 0 1 .464-1.677l.669-.167l-6.845-2.282ZM2 19v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3");
}

</style>

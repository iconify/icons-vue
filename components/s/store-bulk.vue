<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2_cddodz"/><path class="khpj3b6mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-bulk" /></template>
<style>
.a2_cddodz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.khpj3b6mo {
  d: path("M10 9a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6-6v6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M6 9v10a1 1 0 0 0 1 1h2v-3a3 3 0 1 1 6 0v3h2a1 1 0 0 0 1-1V9a1 1 0 0 1 2 0v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V9a1 1 0 0 1 2 0m7 8a1 1 0 0 0-2 0v3h2Z");
}

</style>

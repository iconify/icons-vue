<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v_lhykb4f"/><path class="kgyuo2bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-bottom-right-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kgyuo2bma {
  d: path("M3 2h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1m11 2h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m8-1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2h3a1 1 0 0 1 1 1M4 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m5 11V10a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1m2-10v9h9v-9ZM2 21v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1");
}

.v_lhykb4f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 10a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1Z");
}

</style>

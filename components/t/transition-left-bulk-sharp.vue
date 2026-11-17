<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mnmhpfbqa"/><path class="lw---db3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transition-left-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lw---db3e {
  d: path("m7.018 9.568l1.275-1.275a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414l1.304 1.304A7.001 7.001 0 0 1 19 10v2a1 1 0 0 1-2 0v-2a5 5 0 0 0-9.982-.432");
}

.mnmhpfbqa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0m12 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>

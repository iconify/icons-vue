<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rufoxdbmp"/><path class="qdg3ckb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-search-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qdg3ckb6j {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m10.708 8.293l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415M10 14a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.rufoxdbmp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>

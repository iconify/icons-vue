<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qk8aco53k"/><path class="xtoviob-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:printer-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qk8aco53k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 6a5 5 0 0 1 5 5v3a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4v-3a5 5 0 0 1 5-5Zm-7 6h4a1 1 0 0 0 0-2h-4a1 1 0 0 0 0 2");
}

.xtoviob-l {
  d: path("M10 2h4a4.98 4.98 0 0 1 3.536 1.464A5 5 0 0 1 19 7a1 1 0 0 1-2 0a3 3 0 0 0-3-3h-4c-.796 0-1.56.316-2.122.88A3 3 0 0 0 7 6.998V7a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 10 2m4 8a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm-9 8v-.001A4 4 0 0 1 9 14h6a4 4 0 0 1 0 8H9a4 4 0 0 1-4-4m4 2h6a2 2 0 1 0 0-4H9a2 2 0 1 0 0 4");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ya5luooll"/><path class="ani8f2edy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:page-margins-bulk-round" /></template>
<style>
.ani8f2edy {
  d: path("M11 6h2a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m-1 9a.997.997 0 0 0 1 1h2a.997.997 0 0 0 1-1V9a.997.997 0 0 0-1-1h-2a.997.997 0 0 0-1 1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ya5luooll {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2h6a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m1 13a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1Z");
}

</style>

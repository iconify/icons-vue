<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ojsfkpbfl"/><path class="yjowrxb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-moon-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ojsfkpbfl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15a7 7 0 1 1-14 0c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 8a1 1 0 0 1 .781 1.625a3.267 3.267 0 0 0 3.621 5.131c.353-.121.682-.303.973-.537A1 1 0 0 1 16 15");
}

.yjowrxb7j {
  d: path("M11 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm5.243 3.343l1.414-1.414a1 1 0 1 1 1.414 1.414l-1.414 1.414a.999.999 0 1 1-1.414-1.414m-2.875 1.898c.55.199 1.048.516 1.46.931c.415.412.732.91.931 1.46a1 1 0 0 1-1.88.684a2 2 0 0 0-1.195-1.195a1 1 0 0 1 .684-1.88M19 11h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2");
}

</style>

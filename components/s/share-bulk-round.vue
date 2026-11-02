<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="abw49rb6f"/><path class="uoh9-lbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-bulk-round" /></template>
<style>
.abw49rb6f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 14a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.uoh9-lbcz {
  d: path("M14.293 6.707L13 5.414V13a1 1 0 0 1-2 0V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414M5 14v3a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3v-3a3 3 0 0 0-3-3a1 1 0 0 1 0-2a5 5 0 0 1 3.536 1.464A4.98 4.98 0 0 1 21 14v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-3c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 8 9a1 1 0 0 1 0 2a3 3 0 0 0-3 3");
}

</style>

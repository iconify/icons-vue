<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ghgy_mbzi"/><path class="xyxt1gbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:segmented-control-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ghgy_mbzi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19H7a5 5 0 0 1-5-5Z");
}

.xyxt1gbec {
  d: path("M5 14v-4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2m12-3h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>

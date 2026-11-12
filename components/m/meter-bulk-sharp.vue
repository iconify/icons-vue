<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="df5n5-nbs"/><path class="u_lgrnbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.df5n5-nbs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

.u_lgrnbsf {
  d: path("M9 4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm1 2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm-9 5V8H7v3Zm4-3h-2v3h2Zm2 3h2V8h-2Zm-7 6h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>

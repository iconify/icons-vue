<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3h0twbhh"/><path class="ycbtoccfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:picture-in-picture-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l3h0twbhh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

.ycbtoccfo {
  d: path("M13 11h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6m0 4h2a1 1 0 0 0 0-2h-2a1 1 0 0 0 0 2");
}

</style>

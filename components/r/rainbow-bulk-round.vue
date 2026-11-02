<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tzdt6p-wh"/><path class="bg5ftrbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rainbow-bulk-round" /></template>
<style>
.bg5ftrbpa {
  d: path("M2 15C2 9.477 6.477 5 12 5s10 4.477 10 10v3a1 1 0 0 1-2 0v-3a8 8 0 0 0-16 0v3a1 1 0 0 1-2 0Zm6 0a4 4 0 0 1 8 0v3a1 1 0 0 1-2 0v-3a2 2 0 1 0-4 0v3a1 1 0 0 1-2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tzdt6p-wh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 15a7 7 0 1 1 14 0v3a1 1 0 0 1-2 0v-3a5 5 0 0 0-10 0v3a1 1 0 0 1-2 0Z");
}

</style>

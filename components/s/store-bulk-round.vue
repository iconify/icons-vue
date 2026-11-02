<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rygzlfbmy"/><path class="topkzebac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rygzlfbmy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8");
}

.topkzebac {
  d: path("M10 9a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6-6v6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M6 9v8a3 3 0 0 0 3 3v-3a3 3 0 1 1 6 0v3a3 3 0 0 0 3-3V9a1 1 0 0 1 2 0v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V9a1 1 0 0 1 2 0m7 8a1 1 0 0 0-2 0v3h2Z");
}

</style>

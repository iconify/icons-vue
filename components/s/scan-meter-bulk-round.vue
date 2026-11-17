<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q88bgyn6c"/><path class="ulg2yk2-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-meter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q88bgyn6c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 9h10a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2m0 2v2h2v-2Zm4 2h2v-2h-2Zm4 0h2v-2h-2Z");
}

.ulg2yk2-d {
  d: path("M2 7c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 7 2a1 1 0 0 1 0 2a2.98 2.98 0 0 0-2.121.879A2.98 2.98 0 0 0 4 7a1 1 0 0 1-2 0m15-5c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 7a1 1 0 0 1-2 0a2.98 2.98 0 0 0-.879-2.121A2.98 2.98 0 0 0 17 4a1 1 0 0 1 0-2M5 11a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Zm2 0v2h2v-2Zm4 0v2h2v-2Zm6 2v-2h-2v2ZM7 22a4.98 4.98 0 0 1-3.536-1.464A5 5 0 0 1 2 17a1 1 0 0 1 2 0a2.98 2.98 0 0 0 .879 2.121A2.98 2.98 0 0 0 7 20a1 1 0 0 1 0 2m15-5c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 17 22a1 1 0 0 1 0-2a2.98 2.98 0 0 0 2.121-.879A2.98 2.98 0 0 0 20 17a1 1 0 0 1 2 0");
}

</style>

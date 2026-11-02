<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f--irmbsa"/><path class="t7cy-21bh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-merge-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f--irmbsa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5Z");
}

.t7cy-21bh {
  d: path("M13 4v4h7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h7V4a1 1 0 0 1 2 0M4 14h16a1 1 0 0 1 0 2h-7v4a1 1 0 0 1-2 0v-4H4a1 1 0 0 1 0-2");
}

</style>

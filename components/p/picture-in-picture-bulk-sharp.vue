<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jrbq1jb7d"/><path class="eyxwtlbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:picture-in-picture-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eyxwtlbuz {
  d: path("M10 12a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Zm2 3h4v-2h-4Z");
}

.jrbq1jb7d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>

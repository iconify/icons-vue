<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y861dxbvp"/><path class="q_f5o-xmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:workflow-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q_f5o-xmk {
  d: path("M6 11a1 1 0 0 1 2 0v2a3 3 0 0 0 3 3h2a1 1 0 0 1 0 2h-2a5 5 0 0 1-5-5Z");
}

.y861dxbvp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm10 10a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vg5_884cz"/><path class="dan8a8mmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smoke-detector-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dan8a8mmd {
  d: path("M17 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm-6.348 9.092c.299.411.473.898.473 1.408c0 1.089-.746 1.928-1.678 2.394c-.204.103-.572.338-.572.606s.368.503.572.606a1 1 0 1 1-.894 1.788c-.469-.234-.895-.559-1.205-.986a2.4 2.4 0 0 1-.473-1.408c0-1.089.746-1.928 1.678-2.394c.204-.103.572-.338.572-.606s-.368-.503-.572-.606a.999.999 0 1 1 .894-1.788c.469.234.895.559 1.205.986m6 0c.299.411.473.898.473 1.408c0 1.089-.746 1.928-1.678 2.394c-.204.103-.572.338-.572.606s.368.503.572.606a1 1 0 1 1-.894 1.788c-.469-.234-.895-.559-1.205-.986a2.4 2.4 0 0 1-.473-1.408c0-1.089.746-1.928 1.678-2.394c.204-.103.572-.338.572-.606s-.368-.503-.572-.606a1 1 0 1 1 .894-1.788c.469.234.895.559 1.205.986");
}

.vg5_884cz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 8a3 3 0 1 1 0-6h14a3 3 0 1 1 0 6h-1v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V8Z");
}

</style>

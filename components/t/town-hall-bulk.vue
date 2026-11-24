<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tu_9w-j3h"/><path class="ep_hx2qmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:town-hall-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ep_hx2qmk {
  d: path("M6 8a6 6 0 1 1 12 0A6 6 0 0 1 6 8m9.686-1.557a4.001 4.001 0 1 0-7.37 3.116a4.001 4.001 0 0 0 7.37-3.116M13 7h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1V6a1 1 0 0 1 2 0ZM9 19a3 3 0 1 1 6 0v2a1 1 0 0 1-2 0v-2a1 1 0 0 0-2 0v2a1 1 0 0 1-2 0Z");
}

.tu_9w-j3h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 8a6 6 0 1 1 12 0v6h1a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a3 3 0 0 1 3-3h1Z");
}

</style>

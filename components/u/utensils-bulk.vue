<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xq3j7aczf"/><path class="crrg8cbrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils-bulk" /></template>
<style>
.crrg8cbrc {
  d: path("M4 9a.997.997 0 0 0 1 1h1V3a1 1 0 0 1 2 0v7h1a.997.997 0 0 0 1-1V3a1 1 0 0 1 2 0v6a3 3 0 0 1-3 3H8v9a1 1 0 0 1-2 0v-9H5a3 3 0 0 1-3-3V3a1 1 0 0 1 2 0Zm18 12a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xq3j7aczf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14a1 1 0 0 1-1 1h-3a3 3 0 0 1-3-3V8c0-1.596.627-3.117 1.757-4.243a6 6 0 0 1 1.907-1.285A5.9 5.9 0 0 1 21 2a1 1 0 0 1 1 1Z");
}

</style>

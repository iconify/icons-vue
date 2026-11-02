<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vkd5_obwx"/><path class="nuz_rzbsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nuz_rzbsh {
  d: path("M8 5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v3a1 1 0 0 1-2 0V5a.997.997 0 0 0-1-1h-2a.997.997 0 0 0-1 1v3a1 1 0 0 1-2 0Zm5 5v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0m-3 9a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1v-3a1 1 0 0 1 2 0v3a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-3a1 1 0 0 1 2 0Z");
}

.vkd5_obwx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 12a6 6 0 1 1 12 0a6 6 0 0 1-12 0");
}

</style>

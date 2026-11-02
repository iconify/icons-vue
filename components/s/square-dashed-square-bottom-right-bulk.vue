<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f19k37b6h"/><path class="qi-cd8bhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-bottom-right-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f19k37b6h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 12a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3Z");
}

.qi-cd8bhn {
  d: path("M5 2h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0V5a3 3 0 0 1 3-3m9 2h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m8 1v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3 3 0 0 1 3 3M4 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m5 2a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3Zm2 0v7a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1v-7a1 1 0 0 0-1-1h-7a.997.997 0 0 0-1 1m-9 7v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3");
}

</style>

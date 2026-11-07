<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ao3978b2g"/><path class="g6qhq3bhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-bulk" /></template>
<style>
.ao3978b2g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7V6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g6qhq3bhs {
  d: path("M8 8v12a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4-1h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>

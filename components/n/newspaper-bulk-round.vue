<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d7qp75vtp"/><path class="g6qhq3bhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d7qp75vtp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.083 7.083A5.01 5.01 0 0 1 11 3h6a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4.083-4.917");
}

.g6qhq3bhs {
  d: path("M8 8v12a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4-1h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>

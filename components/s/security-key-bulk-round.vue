<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="slztfoafr"/><path class="y7wvd8bru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-key-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.slztfoafr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.y7wvd8bru {
  d: path("M20 8a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-5a1 1 0 0 1 0-2h5v-1h-1a1 1 0 0 1 0-2h1v-1h-5a1 1 0 0 1 0-2Zm-10 5a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>

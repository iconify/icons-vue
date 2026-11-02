<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ga9nhbbxi"/><path class="j-759vb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:venus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ga9nhbbxi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 8a6 6 0 1 1 12 0A6 6 0 0 1 6 8");
}

.j-759vb2i {
  d: path("M13 16h2a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0v-3H9a1 1 0 0 1 0-2h2v-3a1 1 0 0 1 2 0Z");
}

</style>

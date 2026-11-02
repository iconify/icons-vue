<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rm39oqpfh"/><path class="wsry58p4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rm39oqpfh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8");
}

.wsry58p4i {
  d: path("M13 14v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>

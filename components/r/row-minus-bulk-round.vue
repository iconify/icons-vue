<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rm39oqpfh"/><path class="xniqahzqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-minus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rm39oqpfh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8");
}

.xniqahzqr {
  d: path("M9 16h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>

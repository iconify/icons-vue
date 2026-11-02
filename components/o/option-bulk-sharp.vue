<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pkcxx5m2i"/><path class="td9ir9nnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:option-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pkcxx5m2i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 6h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

.td9ir9nnc {
  d: path("M9 6c.351 0 .677.184.857.486L15.566 16H21a1 1 0 0 1 0 2h-6a1 1 0 0 1-.857-.486L8.434 8H3a1 1 0 0 1 0-2Z");
}

</style>

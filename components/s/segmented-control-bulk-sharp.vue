<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h6nnvw4ju"/><path class="o5s8unncj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:segmented-control-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h6nnvw4ju {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.o5s8unncj {
  d: path("M5 15V9a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1m12-4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>

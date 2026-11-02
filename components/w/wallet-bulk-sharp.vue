<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jrbq1jb7d"/><path class="a1bxymbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallet-bulk-sharp" /></template>
<style>
.a1bxymbdw {
  d: path("M21 10h-5v4h5a1 1 0 0 1 0 2h-6a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h6a1 1 0 0 1 0 2m-3 1h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jrbq1jb7d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>

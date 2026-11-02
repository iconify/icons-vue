<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qrvln_b7u"/><path class="gyq4nzbrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:standing-desk-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gyq4nzbrx {
  d: path("M4.293 3.293a1 1 0 0 1 1.414 0l2 2a.999.999 0 1 1-1.414 1.414L5 5.414L3.707 6.707a.999.999 0 1 1-1.414-1.414Zm-.586 6L5 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M17 12v3h2a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0v-2a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v2a1 1 0 0 1-2 0v-2a3 3 0 0 1 3-3h10v-3a1 1 0 0 1 2 0");
}

.qrvln_b7u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 6a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-6a3 3 0 0 1-3-3Z");
}

</style>

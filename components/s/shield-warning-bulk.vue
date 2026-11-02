<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sf2-14icu"/><path class="w9izdfbjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sf2-14icu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2h12a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3");
}

.w9izdfbjt {
  d: path("M13 8v4a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>

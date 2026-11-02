<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="axh13e6sy"/><path class="ds6id8wtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-palm-bulk" /></template>
<style>
.axh13e6sy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.247 16.659L12 9.519l-6.247 7.14a1.002 1.002 0 0 1-1.751-.593a8.45 8.45 0 0 1 .449-3.352a8.6 8.6 0 0 1 1.874-3.077l-3.215.357a1 1 0 0 1-1.068-1.28a6 6 0 0 1 .787-1.669a5.7 5.7 0 0 1 1.18-1.273a6 6 0 0 1 4.7-1.205A5.77 5.77 0 0 1 12 6.316a5.77 5.77 0 0 1 3.291-1.749c2.263-.372 4.586.571 5.88 2.478a6 6 0 0 1 .787 1.669a1 1 0 0 1-1.068 1.28l-3.215-.357a8.5 8.5 0 0 1 2.323 6.429a1.002 1.002 0 0 1-1.751.593");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ds6id8wtw {
  d: path("M11 21V8a1 1 0 0 1 2 0v13a1 1 0 0 1-2 0");
}

</style>

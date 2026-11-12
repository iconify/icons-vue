<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hhum8kbmu"/><path class="p6d3vccvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-lock-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hhum8kbmu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1");
}

.p6d3vccvd {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m17 8a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2a3 3 0 1 1 6 0m-2 0a1 1 0 0 0-2 0Z");
}

</style>

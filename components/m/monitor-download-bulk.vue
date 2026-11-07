<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x9qbi2awd"/><path class="zps4gabhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x9qbi2awd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.zps4gabhb {
  d: path("M8.293 11.707a.999.999 0 1 1 1.414-1.414L11 11.586V7a1 1 0 0 1 2 0v4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0ZM15 21H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ixmbu2v_y"/><path class="dh66chbzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-warning-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dh66chbzf {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m15 7v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

.ixmbu2v_y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>

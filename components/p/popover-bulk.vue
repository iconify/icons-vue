<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oia9v2b2x"/><path class="gzypby2pf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:popover-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gzypby2pf {
  d: path("M7 11h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

.oia9v2b2x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h3.5l2.7-3.6a1 1 0 0 1 1.6 0L15.5 6Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dcvx-qzrl"/><path class="jtacai2bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dcvx-qzrl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.jtacai2bp {
  d: path("M16 20a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0Zm-9.707-5.707L8.586 12L6.293 9.707a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

</style>

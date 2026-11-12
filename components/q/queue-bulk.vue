<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r1ecsubba"/><path class="zgolppbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:queue-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r1ecsubba {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm0 12a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Z");
}

.zgolppbvf {
  d: path("M17 3a1 1 0 0 1 2 0v15.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.414L17 18.586Z");
}

</style>

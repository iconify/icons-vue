<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eo6jdx22g"/><path class="zgolppbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:queue-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eo6jdx22g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm0 12a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.zgolppbvf {
  d: path("M17 3a1 1 0 0 1 2 0v15.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.414L17 18.586Z");
}

</style>

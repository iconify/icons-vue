<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zqvzu9bgl"/><path class="khv5mjb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:replace-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.khv5mjb9y {
  d: path("M7 5v2.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L5 7.586V5a3 3 0 0 1 3-3h3a1 1 0 0 1 0 2H8a1 1 0 0 0-1 1m9-3h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2m0 6h4V4h-4Z");
}

.zqvzu9bgl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 16a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Z");
}

</style>

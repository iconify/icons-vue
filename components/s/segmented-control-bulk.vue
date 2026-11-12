<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="avx8xbi3l"/><path class="xyxt1gbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:segmented-control-bulk" /></template>
<style>
.avx8xbi3l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xyxt1gbec {
  d: path("M5 14v-4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2m12-3h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>

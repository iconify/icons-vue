<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xdides93p"/><path class="rzz27iuhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rzz27iuhk {
  d: path("M7.158 8.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

.xdides93p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h5c1.039 0 1.992.578 2.707 1.293l6 6a2.414 2.414 0 0 1 0 3.414l-6 6a2.414 2.414 0 0 1-3.414 0l-6-6C3.578 12.992 3 12.039 3 11V6a3 3 0 0 1 3-3");
}

</style>

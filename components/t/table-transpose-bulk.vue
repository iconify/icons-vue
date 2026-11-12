<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oeow3hbsv"/><path class="noe1vbbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.noe1vbbmn {
  d: path("M13 19v-4a1 1 0 0 1 2 0v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L16.414 18H18a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1");
}

.oeow3hbsv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2Zm-8 8a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Z");
}

</style>

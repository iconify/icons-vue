<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q8edtyblu"/><path class="zp8xlikkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q8edtyblu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.zp8xlikkn {
  d: path("M2 5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm20 0v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3 3 0 0 1 3 3M4 5v7a.997.997 0 0 0 1 1h7a.997.997 0 0 0 1-1V5a.997.997 0 0 0-1-1H5a.997.997 0 0 0-1 1m16 9v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0M2 19v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3m17 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0v1a3 3 0 0 1-3 3m-9-2h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>

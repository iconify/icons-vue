<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="baxsy5bss"/><path class="b8gcl_amr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-bulk" /></template>
<style>
.b8gcl_amr {
  d: path("M5 2h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0V5a3 3 0 0 1 3-3m4 3a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3Zm2 0v7a.997.997 0 0 0 1 1h7a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-7a.997.997 0 0 0-1 1m-7 5v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-2 9v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3m17 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0v1a3 3 0 0 1-3 3m-9-2h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.baxsy5bss {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>

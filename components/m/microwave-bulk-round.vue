<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="biwhojbir"/><path class="tqvc0acot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microwave-bulk-round" /></template>
<style>
.biwhojbir {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19H7a5 5 0 0 1-5-5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tqvc0acot {
  d: path("M6 10a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Zm12-2v6a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0M8 10v2a.997.997 0 0 0 1 1h2a.997.997 0 0 0 1-1v-2a.997.997 0 0 0-1-1H9a.997.997 0 0 0-1 1m0 8v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0m10 0v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0");
}

</style>

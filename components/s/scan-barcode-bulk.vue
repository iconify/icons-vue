<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d2rzqrb0o"/><path class="a9k6yfb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-barcode-bulk" /></template>
<style>
.a9k6yfb-x {
  d: path("M2 5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0Zm17-3a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2ZM5 22a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2Zm17-3a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d2rzqrb0o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 16a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Z");
}

</style>

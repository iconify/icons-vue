<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x4hv9vbpo"/><path class="u7ffy3qxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u7ffy3qxn {
  d: path("M16.707 11.293a.999.999 0 1 1-1.414 1.414l-4-4a.999.999 0 1 1 1.414-1.414ZM20 19a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Z");
}

.x4hv9vbpo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 16c0-.265.105-.52.293-.707l12-12a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-12 12A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w4t9vcc-b"/><path class="xniqahzqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-minus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.w4t9vcc-b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

.xniqahzqr {
  d: path("M9 16h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>

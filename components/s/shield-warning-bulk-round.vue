<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lnef9ckzr"/><path class="w9izdfbjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lnef9ckzr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2h8a5 5 0 0 1 5 5v3c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V7a5 5 0 0 1 5-5");
}

.w9izdfbjt {
  d: path("M13 8v4a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m1ausq56u"/><path class="hy8s_bctq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-vibrate-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hy8s_bctq {
  d: path("M2.051 6.316a1.001 1.001 0 0 1 1.898-.632l1 3c.068.205.068.427 0 .632L4.054 12l.895 2.684c.068.205.068.427 0 .632l-1 3a1.001 1.001 0 0 1-1.898-.632L2.946 15l-.895-2.684a1 1 0 0 1 0-.632L2.946 9ZM21.054 9l.895 2.684c.068.205.068.427 0 .632L21.054 15l.895 2.684a1.001 1.001 0 0 1-1.898.632l-1-3a1 1 0 0 1 0-.632L19.946 12l-.895-2.684a1 1 0 0 1 0-.632l1-3a1.001 1.001 0 0 1 1.898.632Z");
}

.m1ausq56u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

</style>

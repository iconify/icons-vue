<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lqgu2ibkx"/><path class="a8r8s_qgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-bulk-round" /></template>
<style>
.a8r8s_qgx {
  d: path("M4 6.998V7a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 7 2a1.002 1.002 0 0 1 .707 1.707A1 1 0 0 1 7 4q-.154 0-.309.015a2.98 2.98 0 0 0-1.812.864A2.97 2.97 0 0 0 4 6.998M16 3a1 1 0 0 1 1-1a5 5 0 0 1 3.536 1.464A4.97 4.97 0 0 1 22 7a1 1 0 0 1-2 0a2.96 2.96 0 0 0-.879-2.121A2.96 2.96 0 0 0 17 4a1 1 0 0 1-1-1m-.653 10.933l2.36 2.36a.999.999 0 1 1-1.414 1.414l-2.36-2.36a5.244 5.244 0 1 1 1.414-1.414m-1.342-1.712A3.244 3.244 0 1 0 7.994 9.78a3.244 3.244 0 0 0 6.011 2.441M2 17a1.002 1.002 0 0 1 1.707-.707A1 1 0 0 1 4 17a3 3 0 0 0 .879 2.121c.566.566 1.32.883 2.121.879a1 1 0 0 1 0 2a5 5 0 0 1-3.536-1.464A4.97 4.97 0 0 1 2 17m19.903.99a5.01 5.01 0 0 1-2.956 3.617A5 5 0 0 1 17 22a1 1 0 0 1 0-2a2.96 2.96 0 0 0 2.121-.879c.566-.566.883-1.32.879-2.121a1 1 0 0 1 2 0c0 .332-.032.665-.097.99");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lqgu2ibkx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.293 7.293a5.243 5.243 0 1 1 7.416 7.414a5.243 5.243 0 0 1-7.416-7.414");
}

</style>

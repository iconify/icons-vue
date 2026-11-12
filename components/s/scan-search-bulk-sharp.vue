<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lqgu2ibkx"/><path class="ezl3at_yv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ezl3at_yv {
  d: path("M3 2h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1m14 0h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2m-1.653 11.933l2.36 2.36a.999.999 0 1 1-1.414 1.414l-2.36-2.36a5.244 5.244 0 1 1 1.414-1.414m-1.342-1.712A3.244 3.244 0 1 0 7.994 9.78a3.244 3.244 0 0 0 6.011 2.441M2 21v-4a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1m19 1h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1");
}

.lqgu2ibkx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.293 7.293a5.243 5.243 0 1 1 7.416 7.414a5.243 5.243 0 0 1-7.416-7.414");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lqgu2ibkx"/><path class="x-44oz90j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lqgu2ibkx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.293 7.293a5.243 5.243 0 1 1 7.416 7.414a5.243 5.243 0 0 1-7.416-7.414");
}

.x-44oz90j {
  d: path("M4.999 2H7a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0V5c0-.796.316-1.559.879-2.121A3 3 0 0 1 4.999 2M22 5v2a1 1 0 0 1-2 0V5c0-.268-.108-.525-.299-.713A.96.96 0 0 0 19 4h-2a1 1 0 0 1 0-2h2a3 3 0 0 1 3 3m-6.653 8.933l2.36 2.36a.999.999 0 1 1-1.414 1.414l-2.36-2.36a5.244 5.244 0 1 1 1.414-1.414m-1.342-1.712A3.244 3.244 0 1 0 7.994 9.78a3.244 3.244 0 0 0 6.011 2.441M2 19v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2H5a3.004 3.004 0 0 1-3-3m17 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0v2a3.004 3.004 0 0 1-3 3");
}

</style>

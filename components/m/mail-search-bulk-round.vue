<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jk557sgwt"/><path class="onk-xib1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jk557sgwt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14v1a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h3a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387a5.08 5.08 0 0 0 6.194 3.348a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1");
}

.onk-xib1i {
  d: path("m19.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586M4.424 6.01l3.283 3.283C8.261 9.847 9.248 10 10 10h2a1 1 0 0 1 0 2h-2c-1.318 0-2.749-.335-3.707-1.293L3.01 7.424A.999.999 0 1 1 4.424 6.01");
}

</style>

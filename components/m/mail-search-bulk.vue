<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c2wkvob0m"/><path class="u_rq7hb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-bulk" /></template>
<style>
.c2wkvob0m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h5a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387a5.08 5.08 0 0 0 6.194 3.348a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u_rq7hb1k {
  d: path("m19.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586m-13-2.414l4.414 4.414c.315.315.825.707 1.293.707h2a1 1 0 0 1 0 2h-2c-1.039 0-1.991-.577-2.707-1.293L2.879 6.293a.999.999 0 1 1 1.414-1.414");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oac49acxn"/><path class="di3f7ccwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.di3f7ccwg {
  d: path("m19.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414M3.707 4.293L9.414 10H12a1 1 0 0 1 0 2H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414m13.586 3a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

.oac49acxn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h7a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387a5.08 5.08 0 0 0 6.194 3.348a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1");
}

</style>

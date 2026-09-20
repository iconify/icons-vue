<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h0f8m9ddk"/><path class="uobcq2kdt"/><path class="jkx1ccc-l"/><path class="cu_k2eb7o"/><path class="gbhlx2b8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:trophy" /></template>
<style>
.cu_k2eb7o {
  d: path("M2.268 4.512a1.003 1.003 0 0 1 1.135.848l.07.489a3.165 3.165 0 0 0 2.62 2.667l-.328 1.968a5.17 5.17 0 0 1-4.277-4.356l-.07-.488a.997.997 0 0 1 .85-1.128m12.311.988a1 1 0 0 0 1 1h2.01a1 1 0 1 0 0-2h-2.01a1 1 0 0 0-1 1");
}

.gbhlx2b8b {
  d: path("M17.732 4.512a1.003 1.003 0 0 0-1.135.848l-.07.489a3.17 3.17 0 0 1-2.62 2.667l.328 1.968a5.17 5.17 0 0 0 4.277-4.356l.07-.488a.997.997 0 0 0-.85-1.128");
}

.h0f8m9ddk {
  d: path("M13.675 4.5H6.227l.635 4.418c1.222 2.623 4.956 2.623 6.178 0zm-7.448-2a2 2 0 0 0-1.98 2.285l.64 4.446q.037.256.144.492c1.925 4.217 7.915 4.217 9.84 0q.107-.236.144-.492l.64-4.446a2 2 0 0 0-1.98-2.285z");
}

.jkx1ccc-l {
  d: path("M8.058 16.5a2.78 2.78 0 0 1 3.786 0zm4.91-1a4.277 4.277 0 0 0-6.033 0l-.796.791c-.632.63-.187 1.709.706 1.709h6.212c.893 0 1.338-1.08.706-1.709zm-7.547-10a1 1 0 0 1-1 1h-2.01a1 1 0 0 1 0-2h2.01a1 1 0 0 1 1 1");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.uobcq2kdt {
  d: path("M8.95 15.5v-3h2v3z");
}

</style>

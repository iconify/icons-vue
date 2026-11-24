<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sowt4_0jd"/><path class="qj1la_erq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-search-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qj1la_erq {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm6.283 12.707l-.003-.002a3.83 3.83 0 1 1 6.031-.798l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.825 3.825 0 0 1-4.614-.614m4-1.414l.001-.002c.343-.343.534-.809.533-1.294a1.82 1.82 0 0 0-.534-1.29h-.001a1.829 1.829 0 1 0 .001 2.586M7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

.sowt4_0jd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8 8v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1");
}

</style>

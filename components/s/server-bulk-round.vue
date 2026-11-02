<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e7wyaz_gg"/><path class="u_zqldigq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e7wyaz_gg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m0 10h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8");
}

.u_zqldigq {
  d: path("M7 6h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 10h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>

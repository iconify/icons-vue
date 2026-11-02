<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h59ep0b-b"/><path class="u_zqldigq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h59ep0b-b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m0 10h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

.u_zqldigq {
  d: path("M7 6h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 10h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>

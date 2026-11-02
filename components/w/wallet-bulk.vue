<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hyle18ydz"/><path class="b4ln4qbpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallet-bulk" /></template>
<style>
.b4ln4qbpd {
  d: path("M21 10h-4a.997.997 0 0 0-1 1v2a.997.997 0 0 0 1 1h4a1 1 0 0 1 0 2h-4a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 0 2m-3 1h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hyle18ydz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
